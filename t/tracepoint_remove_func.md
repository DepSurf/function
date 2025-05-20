# Function: <code>tracepoint_remove_func</code>

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
In kernel/tracepoint.c (ffffffff8113f757)
Location: kernel/tracepoint.c:229
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff81147dcb)
Location: kernel/tracepoint.c:229
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff81151c6b)
Location: kernel/tracepoint.c:233
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff811542d7)
Location: kernel/tracepoint.c:234
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff81160ae7)
Location: kernel/tracepoint.c:234
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff8116fcd7)
Location: kernel/tracepoint.c:233
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff8117d567)
Location: kernel/tracepoint.c:279
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff8118a707)
Location: kernel/tracepoint.c:266
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff81196617)
Location: kernel/tracepoint.c:266
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tracepoint_remove_func(struct tracepoint *tp, struct tracepoint_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811ab260)
Location: kernel/tracepoint.c:266
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
```
**Symbols:**

```
ffffffff811ab260-ffffffff811ab44f: tracepoint_remove_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tracepoint_remove_func(struct tracepoint *tp, struct tracepoint_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811a9220)
Location: kernel/tracepoint.c:336
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
```
**Symbols:**

```
ffffffff811a9220-ffffffff811a9366: tracepoint_remove_func (STB_LOCAL)
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
In kernel/tracepoint.c (ffffffff811a96ab)
Location: kernel/tracepoint.c:396
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff811d329b)
Location: kernel/tracepoint.c:396
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff81207d13)
Location: kernel/tracepoint.c:396
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff81250783)
Location: kernel/tracepoint.c:396
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff81267b1b)
Location: kernel/tracepoint.c:396
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff812814cb)
Location: kernel/tracepoint.c:396
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffff80001020e670)
Location: kernel/tracepoint.c:266
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (c044d1bc)
Location: kernel/tracepoint.c:266
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (c00000000028cf54)
Location: kernel/tracepoint.c:266
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffe00016f40a)
Location: kernel/tracepoint.c:266
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff8118ec37)
Location: kernel/tracepoint.c:266
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff81181db7)
Location: kernel/tracepoint.c:266
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff8118ca07)
Location: kernel/tracepoint.c:266
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff8119a397)
Location: kernel/tracepoint.c:266
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
