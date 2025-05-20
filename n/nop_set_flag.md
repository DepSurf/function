# Function: <code>nop_set_flag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_nop.c (ffffffff81157d30)
Location: kernel/trace/trace_nop.c:63
Inline: False
```
**Symbols:**

```
ffffffff81157d30-ffffffff81157d69: nop_set_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_nop.c (ffffffff811625b0)
Location: kernel/trace/trace_nop.c:63
Inline: False
```
**Symbols:**

```
ffffffff811625b0-ffffffff811625e9: nop_set_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_nop.c (ffffffff8116d8f0)
Location: kernel/trace/trace_nop.c:63
Inline: False
```
**Symbols:**

```
ffffffff8116d8f0-ffffffff8116d929: nop_set_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_nop.c (ffffffff81170c70)
Location: kernel/trace/trace_nop.c:63
Inline: False
```
**Symbols:**

```
ffffffff81170c70-ffffffff81170ca9: nop_set_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_nop.c (ffffffff8117de30)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff8117de30-ffffffff8117de69: nop_set_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_nop.c (0)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff8118cf80-ffffffff8118cf9a: nop_set_flag (STB_LOCAL)
ffffffff8118cf9a-ffffffff8118cfc7: nop_set_flag.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_nop.c (0)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff8119a900-ffffffff8119a91a: nop_set_flag (STB_LOCAL)
ffffffff8119a91a-ffffffff8119a947: nop_set_flag.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_nop.c (0)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff811a8560-ffffffff811a857a: nop_set_flag (STB_LOCAL)
ffffffff811a857a-ffffffff811a85a7: nop_set_flag.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_nop.c (0)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff811b3d70-ffffffff811b3d8a: nop_set_flag (STB_LOCAL)
ffffffff811b3d8a-ffffffff811b3db7: nop_set_flag.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_nop.c (0)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff811cc680-ffffffff811cc69a: nop_set_flag (STB_LOCAL)
ffffffff811cc69a-ffffffff811cc6c7: nop_set_flag.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_nop.c (0)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff811c9bf0-ffffffff811c9c0a: nop_set_flag (STB_LOCAL)
ffffffff81be5ca6-ffffffff81be5cd3: nop_set_flag.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_nop.c (0)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff811cafa0-ffffffff811cafba: nop_set_flag (STB_LOCAL)
ffffffff81bd7abf-ffffffff81bd7aec: nop_set_flag.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_nop.c (0)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff811f71d0-ffffffff811f71ea: nop_set_flag (STB_LOCAL)
ffffffff81cb5f1b-ffffffff81cb5f48: nop_set_flag.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_nop.c (0)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff81230cd0-ffffffff81230cf6: nop_set_flag (STB_LOCAL)
ffffffff81e66f3c-ffffffff81e66f67: nop_set_flag.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_nop.c (ffffffff8127d0b0)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff8127d0b0-ffffffff8127d101: nop_set_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_nop.c (ffffffff81299b50)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff81299b50-ffffffff81299ba1: nop_set_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_nop.c (ffffffff812b51d0)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff812b51d0-ffffffff812b5221: nop_set_flag (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_nop.c (ffff800010232080)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffff800010232080-ffff8000102320d4: nop_set_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_nop.c (c046ddf4)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
c046ddf4-c046de48: nop_set_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_nop.c (c0000000002bc890)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
c0000000002bc890-c0000000002bc910: nop_set_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_nop.c (ffffffe000189a12)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffe000189a12-ffffffe000189a5c: nop_set_flag (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_nop.c (0)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff811ac390-ffffffff811ac3aa: nop_set_flag (STB_LOCAL)
ffffffff811ac3aa-ffffffff811ac3d7: nop_set_flag.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_nop.c (0)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff8119f260-ffffffff8119f27a: nop_set_flag (STB_LOCAL)
ffffffff8119f27a-ffffffff8119f2a7: nop_set_flag.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_nop.c (0)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff811aa160-ffffffff811aa17a: nop_set_flag (STB_LOCAL)
ffffffff811aa17a-ffffffff811aa1a7: nop_set_flag.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int nop_set_flag(struct trace_array *tr, u32 old_flags, u32 bit, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_nop.c (0)
Location: kernel/trace/trace_nop.c:64
Inline: False
```
**Symbols:**

```
ffffffff811b7fa0-ffffffff811b7fba: nop_set_flag (STB_LOCAL)
ffffffff811b7fba-ffffffff811b7fe7: nop_set_flag.cold (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
