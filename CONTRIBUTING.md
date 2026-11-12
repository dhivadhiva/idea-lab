# Contributing to Idea Lab

Thanks for joining in. You don't need to write code to help. You can:

- **Post an idea** you'd like to see built.
- **Upvote ideas you'd use.** Click the arrow on the post, then sort Ideas by **Top** to see what people want most.
- **Comment.** Ask questions, link similar projects, suggest a smaller first version.
- **Build an idea**, or join someone who already is.
- **Share what you built** in Show and tell.

## Posting an idea

1. **Search first.** Check [existing ideas](https://github.com/dhivadhiva/idea-lab/discussions/categories/ideas). If something similar is there, add your angle to that thread instead.
2. **Start a new discussion in [Ideas](https://github.com/dhivadhiva/idea-lab/discussions/new?category=ideas).** The form asks for the problem, the idea, what exists today and the smallest useful version.
3. **Use a clear title.** "A CLI that turns screenshots into Markdown tables" tells people far more than "Cool tool idea".
4. **Stick around.** Answer questions and edit your post as the idea gets sharper.

## Giving feedback

- Prefer **"yes, and..."** to "no, because...". Help make the idea better.
- If something like it already exists, **link it and say how it compares**. That's useful, not a put-down.
- **Upvote instead of commenting "+1".**
- Keep threads on topic. A different idea deserves its own discussion.

## Picking up an idea

1. **Say you're in.** Comment on the idea with "I'd like to build this" and a rough plan for the first version. Others can offer to join you.
2. **Open a kickoff issue.** Use the [Project kickoff](https://github.com/dhivadhiva/idea-lab/issues/new?template=project-kickoff.yml) form and link the idea. The idea is then labelled `status: in-progress`.
3. **Build it wherever you like.** Your own account, an organization, a team repo: all fine. Put a link back to the idea discussion in your README.
4. **Post updates** in the kickoff issue. If you have to stop, just say so; the idea goes back to `status: needs-builder`. No hard feelings.
5. **Ship it.** When there's something to try, post in [Show and tell](https://github.com/dhivadhiva/idea-lab/discussions/new?category=show-and-tell) and link it in the idea thread. The idea gets `status: shipped`.

More than one person can build the same idea. Different takes are welcome.

## Labels

| Label | Meaning |
| --- | --- |
| `status: new` | Just posted, not reviewed yet (added automatically) |
| `status: discussing` | Gathering feedback and shaping the scope |
| `status: needs-builder` | Well defined and waiting for someone to build it |
| `status: in-progress` | Someone is building it |
| `status: shipped` | Built and released |
| `status: parked` | Out of scope or not right now |
| `type: app` | Mobile or desktop app |
| `type: web` | Web app or website |
| `type: cli` | Command-line or developer tool |
| `type: library` | Library, SDK or API |
| `type: extension` | Browser or editor extension, or plugin |
| `type: ai` | AI or machine learning |
| `type: hardware` | Hardware, IoT or electronics |
| `type: game` | Game |
| `good first project` | Small enough for a first-time builder |
| `help wanted` | The builder is looking for teammates |
| `duplicate` | Already posted elsewhere |

## For maintainers: triage

- **New ideas** arrive with `status: new`. Add one or more `type:` labels and move them to `status: discussing`.
- When an idea has a clear problem and a small first version, move it to `status: needs-builder`. Add `good first project` if it fits.
- **Duplicates:** link the original, add `duplicate`, and close the discussion as a duplicate.
- **Spam or abuse:** hide or delete it and follow the [Code of Conduct](CODE_OF_CONDUCT.md).
- **Q&A:** mark the answer that solved the question.
- Pin a few strong `status: needs-builder` ideas now and then so builders can find them.
