```dataviewjs
const token = "38aae19ac11207cd58e683d51ef16784f8001cfd";
const todoist = await fetch("https://api.todoist.com/sync/v9/completed/get_all", {
	headers: {
		"Authorization": "Bearer " + token,
	}
}).then(res => res.json());

const completedTasks = todoist.items.map(task => ({ddd
	content: task.content,
	completedDate: task.completed_date,
}));

const

dv.span("** TITLE **");
const calendarData = {
	defaultEntryIntensity: 1,
	entries: [],
};

for (let task of todoistTasks) {
	calendarData.entries.push({
		date:
	});
}
dv.table(["Task", "Due Date"],
		todoistTasks.map(t => [t.content, t.due ? t.due.date : "No due date"]));
```
