# Changes in PG Synapse 1.147.1+pg.2

Improvements 🙌:

- Disable manhole feature

# Changes in PG Synapse 1.147.1+pg.1

Upstream merge ✨:

- Upstream merge of version v1.147.1 (https://github.com/element-hq/synapse/tree/v1.147.1)

# Changes in PG Synapse 1.144.0+pg.5

Refactor ✨:

- Use version pg-synapse-module==0.1.8 which removes the custom email event

# Changes in PG Synapse 1.144.0+pg.4

Features ✨:

- Install new pg_synapse_module which blocks the creation of public rooms & (all) spaces

# Changes in PG Synapse 1.144.0+pg.3

Improvements 🙌:

- Hide device display names to prevent leaking sensitive information like device model

# Changes in PG Synapse 1.144.0+pg.2

Features ✨:

- Add new hook in which you can enrich the m.room.member event with extra properties


# Changes in PG Synapse 1.144.0+pg.1

Upstream merge ✨:

- Upstream merge of version v1.144.0 (https://github.com/element-hq/synapse/tree/v1.144.0)

# Changes in PG Synapse 1.135.0+pg.3

Improvements 🙌:

- Increase QR-code login time from 1m to 5m

# Changes in PG Synapse 1.135.0+pg.2

Features ✨:

- [pg-main-project#164](https://private-registry/general/pg/pg-main-project/-/issues/164) - adds email field to room heroes


# Changes in PG Synapse 1.135.0+pg.1

Upstream merge ✨:

- Upstream merge of version 1.135.0

Features ✨:

Improvements 🙌:

Bugfix 🐛:

- When plugin is installed with hook check_event_allowed, event is frozen which gives an error when changing power levels in a room (and maybe other use cases). Fix by unfreezing again. #7

# Changes in PG Synapse 1.132.0+pg.1

Features ✨:

-   Change default notification settings for group-chats to SOUND_ACTION

Improvements 🙌:

- Modified Dockerfile so custom CA's can be installed and custom module is installed.
