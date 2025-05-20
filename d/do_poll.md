# Function: <code>do_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81222021)
Location: fs/select.c:781
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81249c2d)
Location: fs/select.c:787
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8125cbfd)
Location: fs/select.c:795
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812697d0)
Location: fs/select.c:839
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8128c080)
Location: fs/select.c:836
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812b28bb)
Location: fs/select.c:837
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812c79cb)
Location: fs/select.c:876
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812e461f)
Location: fs/select.c:871
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812f5fe6)
Location: fs/select.c:871
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff8132ebb0)
Location: fs/select.c:881
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
```
**Symbols:**

```
ffffffff8132ebb0-ffffffff8132ef47: do_poll.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff8133a480)
Location: fs/select.c:881
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
```
**Symbols:**

```
ffffffff8133a480-ffffffff8133a821: do_poll.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff81340990)
Location: fs/select.c:881
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
```
**Symbols:**

```
ffffffff81340990-ffffffff81340d26: do_poll.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (0)
Location: fs/select.c:884
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
```
**Symbols:**

```
ffffffff8138e360-ffffffff8138e6ed: do_poll.constprop.0 (STB_LOCAL)
ffffffff81cc3adf-ffffffff81cc3af3: do_poll.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (0)
Location: fs/select.c:885
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
```
**Symbols:**

```
ffffffff8140f5f0-ffffffff8140f9ac: do_poll.constprop.0 (STB_LOCAL)
ffffffff81e76300-ffffffff81e76315: do_poll.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (0)
Location: fs/select.c:885
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
```
**Symbols:**

```
ffffffff8149a200-ffffffff8149a5d6: do_poll.constprop.0 (STB_LOCAL)
ffffffff820688ae-ffffffff820688cb: do_poll.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (0)
Location: fs/select.c:885
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
```
**Symbols:**

```
ffffffff814cf2d0-ffffffff814cf684: do_poll.constprop.0 (STB_LOCAL)
ffffffff820e81a9-ffffffff820e81c7: do_poll.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (0)
Location: fs/select.c:885
Inline: True
Direct callers:
  - fs/select.c:do_sys_poll
```
**Symbols:**

```
ffffffff81501c10-ffffffff81501fc4: do_poll.constprop.0 (STB_LOCAL)
ffffffff821c4ee6-ffffffff821c4f04: do_poll.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffff8000103a314c)
Location: fs/select.c:871
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (c0585a28)
Location: fs/select.c:871
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (c00000000049ce90)
Location: fs/select.c:871
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffe00026b164)
Location: fs/select.c:871
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ee5c6)
Location: fs/select.c:871
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812df1f6)
Location: fs/select.c:871
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ec3d6)
Location: fs/select.c:871
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812fd3d6)
Location: fs/select.c:871
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
</details>
</li>
</ul>

## Differences
