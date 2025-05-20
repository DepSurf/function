# Function: <code>bpf_get_stack_pe</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_get_stack_pe(u64 ctx, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81233ed0)
Location: kernel/bpf/stackmap.c:673
Inline: False
```
**Symbols:**

```
ffffffff81233ed0-ffffffff81233fe2: bpf_get_stack_pe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_get_stack_pe(u64 ctx, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81237d10)
Location: kernel/bpf/stackmap.c:546
Inline: False
```
**Symbols:**

```
ffffffff81237d10-ffffffff81237e22: bpf_get_stack_pe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_get_stack_pe(u64 ctx, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff812722e0)
Location: kernel/bpf/stackmap.c:552
Inline: False
```
**Symbols:**

```
ffffffff812722e0-ffffffff812723f2: bpf_get_stack_pe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_get_stack_pe(u64 ctx, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff812c1400)
Location: kernel/bpf/stackmap.c:499
Inline: False
```
**Symbols:**

```
ffffffff812c1400-ffffffff812c155d: bpf_get_stack_pe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_get_stack_pe(u64 ctx, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81324cf0)
Location: kernel/bpf/stackmap.c:499
Inline: False
```
**Symbols:**

```
ffffffff81324cf0-ffffffff81324e49: bpf_get_stack_pe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_get_stack_pe(u64 ctx, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81354f50)
Location: kernel/bpf/stackmap.c:496
Inline: False
```
**Symbols:**

```
ffffffff81354f50-ffffffff813550a9: bpf_get_stack_pe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_get_stack_pe(u64 ctx, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff8137d920)
Location: kernel/bpf/stackmap.c:505
Inline: False
```
**Symbols:**

```
ffffffff8137d920-ffffffff8137da79: bpf_get_stack_pe (STB_GLOBAL)
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
