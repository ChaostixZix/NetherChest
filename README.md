# NetherChest
ORIGGINALLY CREATED BY ALEJANDROU
* Summary: An Ender Chest type plugin
* Dependency Plugins: N/A
* PocketMine-MP version: 1.5 (API:3.0.0-ALPHA5)
* OptionalPlugins: -
* Categories: mechanics
* Plugin Access: Databases, Tile Entities
### Configuration

Configuration is through the `config.yml` file.
The following sections are defined:

#### config.yml

*  settings: Configuration settings
	*  global: If true all worlds share the same NetherChest
	*  particles: Decorate NetherChests...
	*  p-ticks: Particle ticks
	*  base-block: Block to use for the base
*  backend: Use YamlMgr or MySqlMgr
*  MySql: MySQL settings. Only used if backend is MySqlMgr to configure MySql settings


# Changes

* 1.1.2:
  - Save Enchancements And Custom Name On Yaml Database Manager
* 1.1.1: Bug fix
  - Fixed item duplication cheat/bug (Reported by @predawnia)
* 1.1.0 : flexibility
  - more configuration, NetherChests can be global now
  - MySQL support
  - Translation: English, Spanish, Dutch
* 1.0.0 : First submission

