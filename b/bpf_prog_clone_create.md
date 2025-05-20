# Function: <code>bpf_prog_clone_create</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8117ec76)
Location: kernel/bpf/core.c:354
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff8118aae6)
Location: kernel/bpf/core.c:436
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff8118f681)
Location: kernel/bpf/core.c:653
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff8119db01)
Location: kernel/bpf/core.c:666
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811b232e)
Location: kernel/bpf/core.c:726
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811c0cde)
Location: kernel/bpf/core.c:962
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811d17c3)
Location: kernel/bpf/core.c:1027
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811ddd43)
Location: kernel/bpf/core.c:1027
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811fa813)
Location: kernel/bpf/core.c:1086
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811f9a63)
Location: kernel/bpf/core.c:1083
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811fa9a0)
Location: kernel/bpf/core.c:1089
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff8122c0d0)
Location: kernel/bpf/core.c:1091
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff8126dce0)
Location: kernel/bpf/core.c:1378
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff812c0ed0)
Location: kernel/bpf/core.c:1352
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff812c0ed0-ffffffff812c0f20: bpf_prog_clone_create.constprop.0 (STB_LOCAL)
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
In kernel/bpf/core.c (ffffffff812e7cc0)
Location: kernel/bpf/core.c:1359
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff812e7cc0-ffffffff812e7d26: bpf_prog_clone_create.constprop.0 (STB_LOCAL)
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
In kernel/bpf/core.c (ffffffff81305fb0)
Location: kernel/bpf/core.c:1401
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff81305fb0-ffffffff81306016: bpf_prog_clone_create.constprop.0 (STB_LOCAL)
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
In kernel/bpf/core.c (ffff80001025ec40)
Location: kernel/bpf/core.c:1027
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (c0492260)
Location: kernel/bpf/core.c:1027
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (c000000000303bc8)
Location: kernel/bpf/core.c:1027
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffe00019ceaa)
Location: kernel/bpf/core.c:1027
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811d6363)
Location: kernel/bpf/core.c:1027
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811c9123)
Location: kernel/bpf/core.c:1027
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811d4133)
Location: kernel/bpf/core.c:1027
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811e2453)
Location: kernel/bpf/core.c:1027
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
</details>
</li>
</ul>

## Differences
