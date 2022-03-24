# tailscale

Runs [Tailscale](https://tailscale.com/) in a container, connecting the host system to a tailnet. `TAILSCALE_AUTH_KEY` must be set to an [auth key](https://tailscale.com/kb/1085/auth-keys) in `.env`. This may not work with certain host configurations; see [tailscale/tailscale#3996](https://github.com/tailscale/tailscale/issues/3996) for more. It works on [TrueNAS SCALE](https://www.truenas.com/truenas-scale/) 22.02.0.1.
