# Function: <code>func_remove</code>

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
In kernel/tracepoint.c (ffffffff8113f75c)
Location: kernel/tracepoint.c:142
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
In kernel/tracepoint.c (ffffffff81147dd0)
Location: kernel/tracepoint.c:142
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
In kernel/tracepoint.c (ffffffff81151c70)
Location: kernel/tracepoint.c:142
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
In kernel/tracepoint.c (ffffffff811542db)
Location: kernel/tracepoint.c:143
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
In kernel/tracepoint.c (ffffffff81160aeb)
Location: kernel/tracepoint.c:143
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
In kernel/tracepoint.c (ffffffff8116fcdc)
Location: kernel/tracepoint.c:143
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
In kernel/tracepoint.c (ffffffff8117d56c)
Location: kernel/tracepoint.c:189
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
In kernel/tracepoint.c (ffffffff8118a70c)
Location: kernel/tracepoint.c:176
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
In kernel/tracepoint.c (ffffffff8119661c)
Location: kernel/tracepoint.c:176
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
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
In kernel/tracepoint.c (ffffffff811ab276)
Location: kernel/tracepoint.c:176
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_remove_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *func_remove(struct tracepoint_func **funcs, struct tracepoint_func *tp_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811a9030)
Location: kernel/tracepoint.c:203
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_remove_func
```
**Symbols:**

```
ffffffff811a9030-ffffffff811a9213: func_remove (STB_LOCAL)
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
In kernel/tracepoint.c (ffffffff811a96af)
Location: kernel/tracepoint.c:232
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
In kernel/tracepoint.c (ffffffff811d329f)
Location: kernel/tracepoint.c:232
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
In kernel/tracepoint.c (ffffffff81207d17)
Location: kernel/tracepoint.c:232
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
In kernel/tracepoint.c (ffffffff81250787)
Location: kernel/tracepoint.c:232
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
In kernel/tracepoint.c (ffffffff81267b1f)
Location: kernel/tracepoint.c:232
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
In kernel/tracepoint.c (ffffffff812814cf)
Location: kernel/tracepoint.c:232
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
In kernel/tracepoint.c (ffff80001020e674)
Location: kernel/tracepoint.c:176
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
In kernel/tracepoint.c (c044d1c0)
Location: kernel/tracepoint.c:176
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
In kernel/tracepoint.c (c00000000028cf58)
Location: kernel/tracepoint.c:176
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
In kernel/tracepoint.c (ffffffe00016f40e)
Location: kernel/tracepoint.c:176
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
In kernel/tracepoint.c (ffffffff8118ec3c)
Location: kernel/tracepoint.c:176
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
In kernel/tracepoint.c (ffffffff81181dbc)
Location: kernel/tracepoint.c:176
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
In kernel/tracepoint.c (ffffffff8118ca0c)
Location: kernel/tracepoint.c:176
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
In kernel/tracepoint.c (ffffffff8119a39c)
Location: kernel/tracepoint.c:176
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
</ul>
