# Function: <code>dev_xdp_prog_count</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9067
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9326
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u8 dev_xdp_prog_count(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a95310)
Location: net/core/dev.c:9316
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:dev_xdp_attach
```
**Symbols:**

```
ffffffff81a95310-ffffffff81a9534b: dev_xdp_prog_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u8 dev_xdp_prog_count(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0b8c0)
Location: net/core/dev.c:9054
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:dev_xdp_attach
```
**Symbols:**

```
ffffffff81c0b8c0-ffffffff81c0b94f: dev_xdp_prog_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u8 dev_xdp_prog_count(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbb8d0)
Location: net/core/dev.c:9041
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:dev_xdp_attach
```
**Symbols:**

```
ffffffff81dbb8d0-ffffffff81dbb95f: dev_xdp_prog_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u8 dev_xdp_prog_count(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2c060)
Location: net/core/dev.c:9049
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:dev_xdp_attach
```
**Symbols:**

```
ffffffff81e2c060-ffffffff81e2c0ef: dev_xdp_prog_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u8 dev_xdp_prog_count(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eea0b0)
Location: net/core/dev.c:9167
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:dev_xdp_attach
```
**Symbols:**

```
ffffffff81eea0b0-ffffffff81eea13f: dev_xdp_prog_count (STB_GLOBAL)
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
