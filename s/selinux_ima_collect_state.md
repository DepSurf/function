# Function: <code>selinux_ima_collect_state</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
char *selinux_ima_collect_state(struct selinux_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ima.c (0)
Location: security/selinux/ima.c:23
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
```
**Symbols:**

```
ffffffff814f5d40-ffffffff814f5f2c: selinux_ima_collect_state (STB_LOCAL)
ffffffff81be333c-ffffffff81be3348: selinux_ima_collect_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
char *selinux_ima_collect_state(struct selinux_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ima.c (0)
Location: security/selinux/ima.c:23
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
```
**Symbols:**

```
ffffffff815507f0-ffffffff81550a88: selinux_ima_collect_state (STB_LOCAL)
ffffffff81cd53f5-ffffffff81cd5455: selinux_ima_collect_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
char *selinux_ima_collect_state(struct selinux_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ima.c (0)
Location: security/selinux/ima.c:23
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
```
**Symbols:**

```
ffffffff815e9ca0-ffffffff815e9f42: selinux_ima_collect_state (STB_LOCAL)
ffffffff81e8820f-ffffffff81e8826f: selinux_ima_collect_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
char *selinux_ima_collect_state(struct selinux_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ima.c (0)
Location: security/selinux/ima.c:23
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
```
**Symbols:**

```
ffffffff81699630-ffffffff816998d5: selinux_ima_collect_state (STB_LOCAL)
ffffffff82073f6a-ffffffff82073fbe: selinux_ima_collect_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
char *selinux_ima_collect_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ima.c (0)
Location: security/selinux/ima.c:21
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
```
**Symbols:**

```
ffffffff816d1ae0-ffffffff816d20d2: selinux_ima_collect_state (STB_LOCAL)
ffffffff820f3b15-ffffffff820f3b54: selinux_ima_collect_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
char *selinux_ima_collect_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ima.c (0)
Location: security/selinux/ima.c:21
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
```
**Symbols:**

```
ffffffff8170e140-ffffffff8170e73d: selinux_ima_collect_state (STB_LOCAL)
ffffffff821d0cb2-ffffffff821d0cf1: selinux_ima_collect_state.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
