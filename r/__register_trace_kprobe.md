# Function: <code>__register_trace_kprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81168160)
Location: kernel/trace/trace_kprobe.c:432
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
**Symbols:**

```
ffffffff81168160-ffffffff81168290: __register_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811757a0)
Location: kernel/trace/trace_kprobe.c:438
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
**Symbols:**

```
ffffffff811757a0-ffffffff811758d0: __register_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81181190)
Location: kernel/trace/trace_kprobe.c:453
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
**Symbols:**

```
ffffffff81181190-ffffffff811812c0: __register_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8118553e)
Location: kernel/trace/trace_kprobe.c:459
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
**Symbols:**

```
ffffffff81183f80-ffffffff81184087: __register_trace_kprobe.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8119322c)
Location: kernel/trace/trace_kprobe.c:459
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
**Symbols:**

```
ffffffff81191ce0-ffffffff81191de7: __register_trace_kprobe.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a8b73)
Location: kernel/trace/trace_kprobe.c:502
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
**Symbols:**

```
ffffffff811a7360-ffffffff811a742b: __register_trace_kprobe.part.9 (STB_LOCAL)
ffffffff811a8c2c-ffffffff811a8c5a: __register_trace_kprobe.part.9.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811b4d17)
Location: kernel/trace/trace_kprobe.c:419
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811b4c40-ffffffff811b4d89: __register_trace_kprobe (STB_LOCAL)
ffffffff811b6ff1-ffffffff811b7038: __register_trace_kprobe.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c3e29)
Location: kernel/trace/trace_kprobe.c:388
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811c3d40-ffffffff811c3e80: __register_trace_kprobe (STB_LOCAL)
ffffffff811c6060-ffffffff811c608c: __register_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811cf8e0)
Location: kernel/trace/trace_kprobe.c:481
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff811cf850-ffffffff811cf92c: __register_trace_kprobe (STB_LOCAL)
ffffffff811d1dc4-ffffffff811d1df0: __register_trace_kprobe.cold (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (ffffffff811ee6b0)
Location: kernel/trace/trace_kprobe.c:480
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
**Symbols:**

```
ffffffff811eba10-ffffffff811ebab2: __register_trace_kprobe.part.0 (STB_LOCAL)
ffffffff811ee7d5-ffffffff811ee801: __register_trace_kprobe.part.0.cold (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (ffffffff811ec900)
Location: kernel/trace/trace_kprobe.c:482
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
**Symbols:**

```
ffffffff811e9b60-ffffffff811e9c02: __register_trace_kprobe.part.0 (STB_LOCAL)
ffffffff81be63df-ffffffff81be640b: __register_trace_kprobe.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811eaa6d)
Location: kernel/trace/trace_kprobe.c:482
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
**Symbols:**

```
ffffffff811eaa30-ffffffff811eab0c: __register_trace_kprobe (STB_LOCAL)
ffffffff81bd809a-ffffffff81bd80c6: __register_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8121b86d)
Location: kernel/trace/trace_kprobe.c:478
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
**Symbols:**

```
ffffffff8121b830-ffffffff8121b90c: __register_trace_kprobe (STB_LOCAL)
ffffffff81cb725b-ffffffff81cb7287: __register_trace_kprobe.cold (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (ffffffff8125dd45)
Location: kernel/trace/trace_kprobe.c:476
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
**Symbols:**

```
ffffffff8125ac20-ffffffff8125acdc: __register_trace_kprobe.part.0 (STB_LOCAL)
ffffffff81e68330-ffffffff81e68359: __register_trace_kprobe.part.0.cold (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (ffffffff812ae7c5)
Location: kernel/trace/trace_kprobe.c:478
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
**Symbols:**

```
ffffffff812ab0e0-ffffffff812ab1d9: __register_trace_kprobe.part.0 (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (ffffffff812d0cd5)
Location: kernel/trace/trace_kprobe.c:478
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
**Symbols:**

```
ffffffff812cd8a0-ffffffff812cd99d: __register_trace_kprobe.part.0 (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (ffffffff812ee7e3)
Location: kernel/trace/trace_kprobe.c:478
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
**Symbols:**

```
ffffffff812eb290-ffffffff812eb39d: __register_trace_kprobe.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffff800010250080)
Location: kernel/trace/trace_kprobe.c:481
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffff800010250080-ffff800010250164: __register_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0482e18)
Location: kernel/trace/trace_kprobe.c:481
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
c0482e18-c0482ecc: __register_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0000000002edcb0)
Location: kernel/trace/trace_kprobe.c:481
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
c0000000002edcb0-c0000000002ede50: __register_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c7f00)
Location: kernel/trace/trace_kprobe.c:481
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff811c7e70-ffffffff811c7f4c: __register_trace_kprobe (STB_LOCAL)
ffffffff811ca3e4-ffffffff811ca410: __register_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811bace0)
Location: kernel/trace/trace_kprobe.c:481
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff811bac50-ffffffff811bad2c: __register_trace_kprobe (STB_LOCAL)
ffffffff811bd1b4-ffffffff811bd1e0: __register_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c5cd0)
Location: kernel/trace/trace_kprobe.c:481
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff811c5c40-ffffffff811c5d1c: __register_trace_kprobe (STB_LOCAL)
ffffffff811c81b4-ffffffff811c81e0: __register_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811d3f30)
Location: kernel/trace/trace_kprobe.c:481
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff811d3ea0-ffffffff811d3f7c: __register_trace_kprobe (STB_LOCAL)
ffffffff811d6414-ffffffff811d6440: __register_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
