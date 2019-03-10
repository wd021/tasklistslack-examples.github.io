![TaskList logo](https://s3.amazonaws.com/tasklistguru/tasklist.png)

<h5>
TaskList is a task manager for your Slack team. Here's a guide on how to use it. Every team member has access to the same commands.
</h5>

## Add Tasks

Use **`/task`** to add a task. Add tags to categorize them (**`@users`** and/or **`#tags`**).

```examples
/task Discuss new design plans! @Allison @Dan #design
/task Prepare for tokyo event @everyone #meetings
/task Walkthrough product v2 @me @Jessica
```

?>&bull; You can use **@me**, **@everyone**, or **@username** for **`@users`**.<br />&bull; If you create a task with no tags, it will automatically be assigned to **@everyone**.

## View Tasks

Use **`/list`** to view a list of all your tags.

```examples
/list
```

Use **`/list [@user/#topic]`** to view tasks for a specific tag.

```examples
/list @everyone
/list @Allison
/list #design
```

?>Responses will be shown as private messages. If you want to post it publically to the whole team, add **`public`** to the end of the command, like **/list #design public**.
