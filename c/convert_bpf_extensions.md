# Function: <code>convert_bpf_extensions</code>

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
In net/core/filter.c (ffffffff81730fe8)
Location: net/core/filter.c:203
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
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
In net/core/filter.c (ffffffff8179bbed)
Location: net/core/filter.c:210
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
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
In net/core/filter.c (ffffffff817c987d)
Location: net/core/filter.c:213
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
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
In net/core/filter.c (ffffffff817e8798)
Location: net/core/filter.c:222
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
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
In net/core/filter.c (ffffffff81863b1e)
Location: net/core/filter.c:224
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
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
In net/core/filter.c (ffffffff818b77c3)
Location: net/core/filter.c:316
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
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
In net/core/filter.c (ffffffff818dda59)
Location: net/core/filter.c:317
Inline: True
Inline callers:
  - net/core/filter.c:bpf_convert_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff819258d0)
Location: net/core/filter.c:317
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff819258d0-ffffffff81925ba5: convert_bpf_extensions.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81957d00)
Location: net/core/filter.c:317
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81957d00-ffffffff81957fd5: convert_bpf_extensions.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool convert_bpf_extensions(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a287d0)
Location: net/core/filter.c:306
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81a287d0-ffffffff81a28aa7: convert_bpf_extensions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool convert_bpf_extensions(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a290f0)
Location: net/core/filter.c:336
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81a290f0-ffffffff81a293c7: convert_bpf_extensions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool convert_bpf_extensions(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a103e0)
Location: net/core/filter.c:336
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81a103e0-ffffffff81a106b8: convert_bpf_extensions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool convert_bpf_extensions(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac2450)
Location: net/core/filter.c:337
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81ac2450-ffffffff81ac2728: convert_bpf_extensions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool convert_bpf_extensions(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3ce50)
Location: net/core/filter.c:338
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81c3ce50-ffffffff81c3d1a9: convert_bpf_extensions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool convert_bpf_extensions(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df11e0)
Location: net/core/filter.c:340
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81df11e0-ffffffff81df1542: convert_bpf_extensions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool convert_bpf_extensions(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e62f00)
Location: net/core/filter.c:340
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81e62f00-ffffffff81e631de: convert_bpf_extensions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool convert_bpf_extensions(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f22340)
Location: net/core/filter.c:345
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81f22340-ffffffff81f2261e: convert_bpf_extensions (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffff800010bf9378)
Location: net/core/filter.c:317
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffff800010bf9378-ffff800010bf9648: convert_bpf_extensions.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool convert_bpf_extensions(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d10d40)
Location: net/core/filter.c:317
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
c0d10d40-c0d11120: convert_bpf_extensions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (c000000000ce0760)
Location: net/core/filter.c:317
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
c000000000ce0760-c000000000ce0b64: convert_bpf_extensions.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffe00077b3f0)
Location: net/core/filter.c:317
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffe00077b3f0-ffffffe00077b660: convert_bpf_extensions.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff818f7cd0)
Location: net/core/filter.c:317
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff818f7cd0-ffffffff818f7fa5: convert_bpf_extensions.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff818b1b00)
Location: net/core/filter.c:317
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff818b1b00-ffffffff818b1dd5: convert_bpf_extensions.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81948d00)
Location: net/core/filter.c:317
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81948d00-ffffffff81948fd5: convert_bpf_extensions.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff8196a610)
Location: net/core/filter.c:317
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff8196a610-ffffffff8196a8e5: convert_bpf_extensions.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
