Here comes a lazy programmer's to-do list manager.

See what those lazy cats said:

  > Life is too short, sometimes I use a to-do list.

  > Where there is a list, there is a mere choice.

  > When in doubt, add one more item to the list.

  > The longer I live, the more I realize the power of plain text.

Available commands:

  todo       # show your to-do list
  todo help  # show usage

  todo add [...]     # make a new plan
  todo done <id>...  # mark a plan done
  todo undo <id>...  # cancel a plan
  todo redo <id>...  # revive a plan
  todo show <id>...  # show full content of a plan

  todo list [todo|done|undo]  # show a more detailed list

  todo history  # show edit history
  todo cleanup  # focus on current plans and forget everything else
  todo rawedit  # edit the list with your editor ($VISUAL or $EDITOR)

Best combinations:

  todo | less
  todo | grep keyword
  todo | shuf -n5

Your to-do list data is located at $HOME/.config/todo/todo.txt

Enjoy your life!
