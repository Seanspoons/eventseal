<!-- ABOUT EVENTSEAL -->
# EventSeal

EventSeal is an open-source platform that helps prevent malformed, duplicate, and late application events from corrupting the team's analytics.

EventSeal is intended for backend and data engineers at small product teams that produce application events but do not have a dedicated data-platform team.

Malformed, duplicated, and late events can quietly produce incorrect dashboards and analytics. Investigating these problems is time-consuming, and manually replaying failed events risks introducing further duplicates.

*EventSeal is in Early Development*

<!-- GETTING STARTED -->
## Getting Started

Once installed and running complete the following steps:

1. Register an application and its event schema.
2. Send a mix of valid, duplicate, and malformed events.
3. Verify which events are accepted and which are quarantined.
4. Inspect one rejected event to identify the validation issue.
5. Correct the rejected event and replay it.
6. Confirm that the event is accepted and that the analytics update did not double-count the event.

<!-- ROADMAP -->
## Roadmap

### Included in v0
- Supports 1 application
- Supports 1 schema version
- Local only
- Dashboard only

### Excluded from v0
- Multiple applications
- Schema evolution
- Authenticaton
- CLI
- API

### Success Criteria
- One application can be registered.
- One schema can be registered.
- EventSeal can locally handle 500 events per-second.
- Replay does not cause an event to be double-counted.


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->
## Contact

Sean Wotherspoon - [LinkedIn - Sean Wotherspoon](https://www.linkedin.com/in/sean-wotherspoon/)

Project Link: [https://github.com/Seanspoons/eventseal](https://github.com/Seanspoons/eventseal)