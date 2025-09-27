# Pridepack Versioning

The versioning shall consist of three elements:

- Major Version `M.u.f`
- Update Version `m.U.f`
- Fix Version `m.u.F`

With `major` being bumped in relation to Minecraft's major release, and the
other ones following [`semver`](https://semver.org)

For example, in [`1.21`](https://minecraft.wiki/w/1.21), the first release is
[`6.0`](https://github.com/Pridecraft-Studios/pridepack/releases/tag/v6.0). If
we had released a version for [`1.20.6`](https://minecraft.wiki/w/1.20.6), the
next version would be `5.2`.

We will consider every new "drop" in the new Minecraft Versioning System as
`major` in the context of Pridepack Versioning. This means 'minor' updates
such as [`1.21.*9*`](https://minecraft.wiki/w/1.21.9) which actually introduce
'major' level changes are treated as such in *our* versioning system.