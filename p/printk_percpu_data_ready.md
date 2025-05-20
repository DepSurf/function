# Function: <code>printk_percpu_data_ready</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool printk_percpu_data_ready();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8112085b)
Location: kernel/printk/printk.c:470
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
**Symbols:**

```
ffffffff8111fe10-ffffffff8111fe22: printk_percpu_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool printk_percpu_data_ready();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111b7f9)
Location: kernel/printk/printk.c:450
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
**Symbols:**

```
ffffffff8111a820-ffffffff8111a832: printk_percpu_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool printk_percpu_data_ready();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111beb9)
Location: kernel/printk/printk.c:438
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk_safe.c:printk_safe_log_store
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
**Symbols:**

```
ffffffff8111ad90-ffffffff8111ada2: printk_percpu_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool printk_percpu_data_ready();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8113c2da)
Location: kernel/printk/printk.c:433
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:printk_trigger_flush
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff81cac425-ffffffff81cac445: printk_percpu_data_ready.cold (STB_LOCAL)
ffffffff8113afa0-ffffffff8113afb8: printk_percpu_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool printk_percpu_data_ready();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115f44a)
Location: kernel/printk/printk.c:438
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:printk_trigger_flush
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff81e5c907-ffffffff81e5c931: printk_percpu_data_ready.cold (STB_LOCAL)
ffffffff8115dc10-ffffffff8115dc32: printk_percpu_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool printk_percpu_data_ready();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81192719)
Location: kernel/printk/printk.c:519
Inline: True
Inline callers:
  - kernel/printk/printk.c:_printk_deferred
  - kernel/printk/printk.c:printk_trigger_flush
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff82058a8f-ffffffff82058ab9: printk_percpu_data_ready.cold (STB_LOCAL)
ffffffff81190ac0-ffffffff81190ae2: printk_percpu_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool printk_percpu_data_ready();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a3fb9)
Location: kernel/printk/printk.c:506
Inline: True
Inline callers:
  - kernel/printk/printk.c:_printk_deferred
  - kernel/printk/printk.c:printk_trigger_flush
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff820d7335-ffffffff820d735f: printk_percpu_data_ready.cold (STB_LOCAL)
ffffffff811a23d0-ffffffff811a23f2: printk_percpu_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool printk_percpu_data_ready();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811b3535)
Location: kernel/printk/printk.c:506
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_trigger_flush
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff821b24c6-ffffffff821b24f0: printk_percpu_data_ready.cold (STB_LOCAL)
ffffffff811b0290-ffffffff811b02b2: printk_percpu_data_ready (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
