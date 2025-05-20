# Function: <code>ethtool_sprintf</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ethtool_sprintf(u8 **data, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a72b10)
Location: net/ethtool/ioctl.c:1831
Inline: False
```
**Symbols:**

```
ffffffff81a72b10-ffffffff81a72b91: ethtool_sprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ethtool_sprintf(u8 **data, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81b2c5d0)
Location: net/ethtool/ioctl.c:1945
Inline: False
```
**Symbols:**

```
ffffffff81b2c5d0-ffffffff81b2c651: ethtool_sprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ethtool_sprintf(u8 **data, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81cb7180)
Location: net/ethtool/ioctl.c:1976
Inline: False
```
**Symbols:**

```
ffffffff81cb7180-ffffffff81cb721d: ethtool_sprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ethtool_sprintf(u8 **data, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81e753e0)
Location: net/ethtool/ioctl.c:1969
Inline: False
```
**Symbols:**

```
ffffffff81e753e0-ffffffff81e7547d: ethtool_sprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ethtool_sprintf(u8 **data, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81ed15c0)
Location: net/ethtool/ioctl.c:1981
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_get_strings
  - drivers/net/virtio_net.c:virtnet_get_strings
```
**Symbols:**

```
ffffffff81ed15c0-ffffffff81ed165d: ethtool_sprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ethtool_sprintf(u8 **data, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81f950a0)
Location: net/ethtool/ioctl.c:2023
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_get_strings
  - drivers/net/virtio_net.c:virtnet_get_strings
  - net/core/selftests.c:net_selftest_get_strings
```
**Symbols:**

```
ffffffff81f950a0-ffffffff81f9513d: ethtool_sprintf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
