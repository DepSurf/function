# Function: <code>func_add</code>

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
In kernel/tracepoint.c (ffffffff8113f959)
Location: kernel/tracepoint.c:95
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
In kernel/tracepoint.c (ffffffff81147fd9)
Location: kernel/tracepoint.c:95
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
In kernel/tracepoint.c (ffffffff81151e79)
Location: kernel/tracepoint.c:95
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
In kernel/tracepoint.c (ffffffff811544b0)
Location: kernel/tracepoint.c:96
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
In kernel/tracepoint.c (ffffffff81160cd5)
Location: kernel/tracepoint.c:96
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
In kernel/tracepoint.c (ffffffff8116f71a)
Location: kernel/tracepoint.c:96
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
In kernel/tracepoint.c (ffffffff8117d76a)
Location: kernel/tracepoint.c:142
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
In kernel/tracepoint.c (ffffffff8118a40a)
Location: kernel/tracepoint.c:129
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
In kernel/tracepoint.c (ffffffff8119631a)
Location: kernel/tracepoint.c:129
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tracepoint_func *func_add(struct tracepoint_func **funcs, struct tracepoint_func *tp_func, int prio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811ab7b0)
Location: kernel/tracepoint.c:129
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffffffff811ab7b0-ffffffff811ab984: func_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tracepoint_func *func_add(struct tracepoint_func **funcs, struct tracepoint_func *tp_func, int prio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811a8800)
Location: kernel/tracepoint.c:135
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_add_func
```
**Symbols:**

```
ffffffff811a8800-ffffffff811a8aec: func_add (STB_LOCAL)
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
In kernel/tracepoint.c (ffffffff811a9a50)
Location: kernel/tracepoint.c:180
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_add_func
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
In kernel/tracepoint.c (ffffffff811d3610)
Location: kernel/tracepoint.c:180
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_add_func
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
In kernel/tracepoint.c (ffffffff81208090)
Location: kernel/tracepoint.c:180
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_add_func
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
In kernel/tracepoint.c (ffffffff81250170)
Location: kernel/tracepoint.c:180
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_add_func
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
In kernel/tracepoint.c (ffffffff81267520)
Location: kernel/tracepoint.c:180
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_add_func
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
In kernel/tracepoint.c (ffffffff81281850)
Location: kernel/tracepoint.c:180
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_add_func
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
In kernel/tracepoint.c (ffff80001020e8e4)
Location: kernel/tracepoint.c:129
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
In kernel/tracepoint.c (c044d470)
Location: kernel/tracepoint.c:129
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
In kernel/tracepoint.c (c00000000028ca54)
Location: kernel/tracepoint.c:129
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
In kernel/tracepoint.c (ffffffe00016f694)
Location: kernel/tracepoint.c:129
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
In kernel/tracepoint.c (ffffffff8118e93a)
Location: kernel/tracepoint.c:129
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
In kernel/tracepoint.c (ffffffff81181aba)
Location: kernel/tracepoint.c:129
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
In kernel/tracepoint.c (ffffffff8118c70a)
Location: kernel/tracepoint.c:129
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
In kernel/tracepoint.c (ffffffff8119a09a)
Location: kernel/tracepoint.c:129
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
