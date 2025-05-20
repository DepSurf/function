# Function: <code>devlink_flash_update_end_notify</code>

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
void devlink_flash_update_end_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194ebd0)
Location: net/core/devlink.c:2773
Inline: False
```
**Symbols:**

```
ffffffff8194ebd0-ffffffff8194ebef: devlink_flash_update_end_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devlink_flash_update_end_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81984e60)
Location: net/core/devlink.c:2800
Inline: False
```
**Symbols:**

```
ffffffff81984e60-ffffffff81984e7f: devlink_flash_update_end_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devlink_flash_update_end_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5e550)
Location: net/core/devlink.c:2928
Inline: False
```
**Symbols:**

```
ffffffff81a5e550-ffffffff81a5e56f: devlink_flash_update_end_notify (STB_GLOBAL)
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
In net/core/devlink.c (ffffffff81a68d4b)
Location: net/core/devlink.c:3406
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
In net/core/devlink.c (ffffffff81a4c10b)
Location: net/core/devlink.c:3609
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
In net/core/devlink.c (ffffffff81b04564)
Location: net/core/devlink.c:4179
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
In net/core/devlink.c (ffffffff81c89e2f)
Location: net/core/devlink.c:4694
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
In net/core/devlink.c (ffffffff81e44a1f)
Location: net/core/devlink.c:4960
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
In net/devlink/dev.c (ffffffff82045694)
Location: net/devlink/dev.c:930
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
In net/devlink/dev.c (ffffffff82104f94)
Location: net/devlink/dev.c:1031
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
void devlink_flash_update_end_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2d478)
Location: net/core/devlink.c:2800
Inline: False
```
**Symbols:**

```
ffff800010c2d478-ffff800010c2d4b8: devlink_flash_update_end_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_flash_update_end_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d43aa8)
Location: net/core/devlink.c:2800
Inline: False
```
**Symbols:**

```
c0d43aa8-c0d43ae0: devlink_flash_update_end_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devlink_flash_update_end_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d25990)
Location: net/core/devlink.c:2800
Inline: False
```
**Symbols:**

```
c000000000d25990-c000000000d259b8: devlink_flash_update_end_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devlink_flash_update_end_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a469e)
Location: net/core/devlink.c:2800
Inline: False
```
**Symbols:**

```
ffffffe0007a469e-ffffffe0007a46d4: devlink_flash_update_end_notify (STB_GLOBAL)
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
void devlink_flash_update_end_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81924cd0)
Location: net/core/devlink.c:2800
Inline: False
```
**Symbols:**

```
ffffffff81924cd0-ffffffff81924cef: devlink_flash_update_end_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devlink_flash_update_end_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dea80)
Location: net/core/devlink.c:2800
Inline: False
```
**Symbols:**

```
ffffffff818dea80-ffffffff818dea9f: devlink_flash_update_end_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devlink_flash_update_end_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81975e60)
Location: net/core/devlink.c:2800
Inline: False
```
**Symbols:**

```
ffffffff81975e60-ffffffff81975e7f: devlink_flash_update_end_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devlink_flash_update_end_notify(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81998350)
Location: net/core/devlink.c:2800
Inline: False
```
**Symbols:**

```
ffffffff81998350-ffffffff8199836f: devlink_flash_update_end_notify (STB_GLOBAL)
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
