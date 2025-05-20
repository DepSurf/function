# Function: <code>devlink_flash_update_begin_notify</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void devlink_flash_update_begin_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194ebb0)
Location: net/core/devlink.c:2765
Inline: False
```
**Symbols:**

```
ffffffff8194ebb0-ffffffff8194ebcf: devlink_flash_update_begin_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devlink_flash_update_begin_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81984e40)
Location: net/core/devlink.c:2792
Inline: False
```
**Symbols:**

```
ffffffff81984e40-ffffffff81984e5f: devlink_flash_update_begin_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devlink_flash_update_begin_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5e530)
Location: net/core/devlink.c:2920
Inline: False
```
**Symbols:**

```
ffffffff81a5e530-ffffffff81a5e54f: devlink_flash_update_begin_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a68ce7)
Location: net/core/devlink.c:3397
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
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
In net/core/devlink.c (ffffffff81a4c0a7)
Location: net/core/devlink.c:3600
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b04500)
Location: net/core/devlink.c:4170
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c89dbb)
Location: net/core/devlink.c:4685
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e449ab)
Location: net/core/devlink.c:4951
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82045628)
Location: net/devlink/dev.c:921
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_nl_cmd_flash_update
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82104f28)
Location: net/devlink/dev.c:1022
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_nl_flash_update_doit
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void devlink_flash_update_begin_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2d438)
Location: net/core/devlink.c:2792
Inline: False
```
**Symbols:**

```
ffff800010c2d438-ffff800010c2d478: devlink_flash_update_begin_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_flash_update_begin_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d43a70)
Location: net/core/devlink.c:2792
Inline: False
```
**Symbols:**

```
c0d43a70-c0d43aa8: devlink_flash_update_begin_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devlink_flash_update_begin_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d25960)
Location: net/core/devlink.c:2792
Inline: False
```
**Symbols:**

```
c000000000d25960-c000000000d25988: devlink_flash_update_begin_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devlink_flash_update_begin_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a4668)
Location: net/core/devlink.c:2792
Inline: False
```
**Symbols:**

```
ffffffe0007a4668-ffffffe0007a469e: devlink_flash_update_begin_notify (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void devlink_flash_update_begin_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81924cb0)
Location: net/core/devlink.c:2792
Inline: False
```
**Symbols:**

```
ffffffff81924cb0-ffffffff81924ccf: devlink_flash_update_begin_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devlink_flash_update_begin_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dea60)
Location: net/core/devlink.c:2792
Inline: False
```
**Symbols:**

```
ffffffff818dea60-ffffffff818dea7f: devlink_flash_update_begin_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devlink_flash_update_begin_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81975e40)
Location: net/core/devlink.c:2792
Inline: False
```
**Symbols:**

```
ffffffff81975e40-ffffffff81975e5f: devlink_flash_update_begin_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devlink_flash_update_begin_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81998330)
Location: net/core/devlink.c:2792
Inline: False
```
**Symbols:**

```
ffffffff81998330-ffffffff8199834f: devlink_flash_update_begin_notify (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
