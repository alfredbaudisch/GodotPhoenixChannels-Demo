# Example Project: Phoenix Channels Client for Godot and GDScript ![Godot 3.*](https://img.shields.io/badge/godot-v3.*-%23478cbf) ![Godot 4.0](https://img.shields.io/badge/godot-v4.0-%23478cbf)

[![Donate using PayPal](https://raw.githubusercontent.com/laurent22/joplin/dev/Assets/WebsiteAssets/images/badges/Donate-PayPal-green.svg)](https://www.paypal.com/donate?hosted_button_id=FC5FTRRE3548C) [![Become a patron](https://raw.githubusercontent.com/laurent22/joplin/dev/Assets/WebsiteAssets/images/badges/Patreon-Badge.svg)](https://www.patreon.com/alfredbaudisch) <a href='https://ko-fi.com/alfredbaudisch' target='_blank'><img height='22' style='border:0px;height:22px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' title='Buy Me a Coffee at ko-fi.com' /></a>

<p align="center">
  <img width="512" height="512" src="https://i.imgur.com/h75l4l7.png">
</p>

Example project for the [Godot Phoenix Channels addon](https://github.com/alfredbaudisch/GodotPhoenixChannels).

## What is this?
GodotPhoenixChannels is a GDScript and [Godot Engine](https://godotengine.org) implementation for the Channels API of the [Phoenix Framework](http://www.phoenixframework.org/). It enables Godot projects and games to connect to Phoenix Channels to leverage the connected massive real-time capabilities of Elixir and Phoenix backends. Compatible with Godot 3.* and Godot 4.0.

## See more
Complete details about the addon and usage instructions are in the addon [repository](https://github.com/alfredbaudisch/GodotPhoenixChannels).

## Links
### Godot 4
- Addon repository: https://github.com/alfredbaudisch/GodotPhoenixChannels/tree/4.0
- [AssetLib](https://godotengine.org/asset-library/asset/1831)
- [Demo](https://github.com/alfredbaudisch/GodotPhoenixChannels-Demo/tree/4.0)

### Godot 3
- Addon repository: https://github.com/alfredbaudisch/GodotPhoenixChannels/tree/3.x
- [AssetLib](https://godotengine.org/asset-library/asset/1843)
- [Demo](https://github.com/alfredbaudisch/GodotPhoenixChannels-Demo)

## Running the sample Elixir Project

A simple Elixir server is available in [Demo/Server](./Demo/Server).

To run it, have Elixir installed, then:
```
cd Demo/server
mix deps.get
iex -S mix phx.server
```

After the server is running, you can run the Godot demo and in the Host field put:
`ws://localhost:4000/socket`.
