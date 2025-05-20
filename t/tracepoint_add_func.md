# Function: <code>tracepoint_add_func</code>

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
In kernel/tracepoint.c (ffffffff8113f93f)
Location: kernel/tracepoint.c:193
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff81147fbf)
Location: kernel/tracepoint.c:193
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff81151e5f)
Location: kernel/tracepoint.c:193
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff8115448f)
Location: kernel/tracepoint.c:194
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff81160caf)
Location: kernel/tracepoint.c:194
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff8116f6fe)
Location: kernel/tracepoint.c:194
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff8117d74e)
Location: kernel/tracepoint.c:240
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff8118a3ee)
Location: kernel/tracepoint.c:227
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff811962fe)
Location: kernel/tracepoint.c:227
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811ab9dc)
Location: kernel/tracepoint.c:227
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tracepoint_add_func(struct tracepoint *tp, struct tracepoint_func *func, int prio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811a8de0)
Location: kernel/tracepoint.c:296
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_register
```
**Symbols:**

```
ffffffff811a8de0-ffffffff811a8f01: tracepoint_add_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tracepoint_add_func(struct tracepoint *tp, struct tracepoint_func *func, int prio, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811a9a10)
Location: kernel/tracepoint.c:323
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_register
  - kernel/tracepoint.c:tracepoint_probe_register_prio_may_exist
```
**Symbols:**

```
ffffffff811a9a10-ffffffff811a9de8: tracepoint_add_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tracepoint_add_func(struct tracepoint *tp, struct tracepoint_func *func, int prio, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/tracepoint.c (0)
Location: kernel/tracepoint.c:323
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_register
  - kernel/tracepoint.c:tracepoint_probe_register_prio_may_exist
```
**Symbols:**

```
ffffffff811d35d0-ffffffff811d395a: tracepoint_add_func (STB_LOCAL)
ffffffff81cb4035-ffffffff81cb4049: tracepoint_add_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tracepoint_add_func(struct tracepoint *tp, struct tracepoint_func *func, int prio, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/tracepoint.c (0)
Location: kernel/tracepoint.c:323
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_register
  - kernel/tracepoint.c:tracepoint_probe_register_prio_may_exist
```
**Symbols:**

```
ffffffff81208050-ffffffff81208405: tracepoint_add_func (STB_LOCAL)
ffffffff81e64f7e-ffffffff81e64f92: tracepoint_add_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tracepoint_add_func(struct tracepoint *tp, struct tracepoint_func *func, int prio, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/tracepoint.c (0)
Location: kernel/tracepoint.c:323
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_register
  - kernel/tracepoint.c:tracepoint_probe_register_prio_may_exist
```
**Symbols:**

```
ffffffff81250130-ffffffff812504e5: tracepoint_add_func (STB_LOCAL)
ffffffff8205ca5d-ffffffff8205ca71: tracepoint_add_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tracepoint_add_func(struct tracepoint *tp, struct tracepoint_func *func, int prio, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/tracepoint.c (0)
Location: kernel/tracepoint.c:323
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_register
  - kernel/tracepoint.c:tracepoint_probe_register_prio_may_exist
```
**Symbols:**

```
ffffffff812674e0-ffffffff8126789c: tracepoint_add_func (STB_LOCAL)
ffffffff820db3fe-ffffffff820db412: tracepoint_add_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tracepoint_add_func(struct tracepoint *tp, struct tracepoint_func *func, int prio, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/tracepoint.c (0)
Location: kernel/tracepoint.c:323
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_register
  - kernel/tracepoint.c:tracepoint_probe_register_prio_may_exist
```
**Symbols:**

```
ffffffff81281810-ffffffff81281bcc: tracepoint_add_func (STB_LOCAL)
ffffffff821b7133-ffffffff821b7147: tracepoint_add_func.cold (STB_LOCAL)
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
In kernel/tracepoint.c (ffff80001020e8c8)
Location: kernel/tracepoint.c:227
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (c044d450)
Location: kernel/tracepoint.c:227
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (c00000000028ca24)
Location: kernel/tracepoint.c:227
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffe00016f684)
Location: kernel/tracepoint.c:227
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff8118e91e)
Location: kernel/tracepoint.c:227
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff81181a9e)
Location: kernel/tracepoint.c:227
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff8118c6ee)
Location: kernel/tracepoint.c:227
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff8119a07e)
Location: kernel/tracepoint.c:227
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool warn</code>
</li>
</ul>
</details>
</li>
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
