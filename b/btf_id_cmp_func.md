# Function: <code>btf_id_cmp_func</code>

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
int btf_id_cmp_func(const void *a, const void *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81223210)
Location: kernel/bpf/btf.c:5746
Inline: False
```
**Symbols:**

```
ffffffff81223210-ffffffff8122321f: btf_id_cmp_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int btf_id_cmp_func(const void *a, const void *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81227cc0)
Location: kernel/bpf/btf.c:5944
Inline: False
```
**Symbols:**

```
ffffffff81227cc0-ffffffff81227ccf: btf_id_cmp_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int btf_id_cmp_func(const void *a, const void *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8125ffb0)
Location: kernel/bpf/btf.c:5997
Inline: False
```
**Symbols:**

```
ffffffff8125ffb0-ffffffff8125ffbf: btf_id_cmp_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int btf_id_cmp_func(const void *a, const void *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812aa7f0)
Location: kernel/bpf/btf.c:6730
Inline: False
```
**Symbols:**

```
ffffffff812aa7f0-ffffffff812aa807: btf_id_cmp_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
int btf_id_cmp_func(const void *a, const void *b);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a50b0)
Location: include/linux/btf.h:453
Inline: False
```
```
In kernel/bpf/verifier.c (ffffffff812ce3f0)
Location: include/linux/btf.h:453
Inline: False
```
```
In kernel/bpf/btf.c (ffffffff81309d60)
Location: include/linux/btf.h:453
Inline: False
```
```
In kernel/bpf/bpf_lsm.c (ffffffff8132cfc0)
Location: include/linux/btf.h:453
Inline: False
```
**Symbols:**

```
ffffffff812a50b0-ffffffff812a50bd: btf_id_cmp_func (STB_LOCAL)
ffffffff812ce3f0-ffffffff812ce3fd: btf_id_cmp_func (STB_LOCAL)
ffffffff81309d60-ffffffff81309d6d: btf_id_cmp_func (STB_LOCAL)
ffffffff8132cfc0-ffffffff8132cfcd: btf_id_cmp_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
int btf_id_cmp_func(const void *a, const void *b);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c7540)
Location: include/linux/btf.h:469
Inline: False
```
```
In kernel/bpf/verifier.c (ffffffff812f5980)
Location: include/linux/btf.h:469
Inline: False
```
```
In kernel/bpf/btf.c (ffffffff81338ba0)
Location: include/linux/btf.h:469
Inline: False
```
```
In kernel/bpf/bpf_lsm.c (ffffffff8135dc10)
Location: include/linux/btf.h:469
Inline: False
```
```
In net/core/filter.c (ffffffff81e5c3a0)
Location: include/linux/btf.h:469
Inline: False
```
```
In net/core/xdp.c (ffffffff81e78080)
Location: include/linux/btf.h:469
Inline: False
```
**Symbols:**

```
ffffffff812c7540-ffffffff812c754d: btf_id_cmp_func (STB_LOCAL)
ffffffff812f5980-ffffffff812f598d: btf_id_cmp_func (STB_LOCAL)
ffffffff81338ba0-ffffffff81338bad: btf_id_cmp_func (STB_LOCAL)
ffffffff8135dc10-ffffffff8135dc1d: btf_id_cmp_func (STB_LOCAL)
ffffffff81e5c3a0-ffffffff81e5c3ad: btf_id_cmp_func (STB_LOCAL)
ffffffff81e78080-ffffffff81e7808d: btf_id_cmp_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
int btf_id_cmp_func(const void *a, const void *b);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e3f00)
Location: include/linux/btf.h:480
Inline: False
```
```
In kernel/bpf/verifier.c (ffffffff81314780)
Location: include/linux/btf.h:480
Inline: False
```
```
In kernel/bpf/btf.c (ffffffff8135ecd0)
Location: include/linux/btf.h:480
Inline: False
```
```
In kernel/bpf/bpf_lsm.c (ffffffff813869e0)
Location: include/linux/btf.h:480
Inline: False
```
```
In fs/verity/measure.c (ffffffff81571990)
Location: include/linux/btf.h:480
Inline: False
```
```
In net/core/filter.c (ffffffff81f1b790)
Location: include/linux/btf.h:480
Inline: False
```
```
In net/core/xdp.c (ffffffff81f38040)
Location: include/linux/btf.h:480
Inline: False
```
**Symbols:**

```
ffffffff812e3f00-ffffffff812e3f0d: btf_id_cmp_func (STB_LOCAL)
ffffffff81314780-ffffffff8131478d: btf_id_cmp_func (STB_LOCAL)
ffffffff8135ecd0-ffffffff8135ecdd: btf_id_cmp_func (STB_LOCAL)
ffffffff813869e0-ffffffff813869ed: btf_id_cmp_func (STB_LOCAL)
ffffffff81571990-ffffffff8157199d: btf_id_cmp_func (STB_LOCAL)
ffffffff81f1b790-ffffffff81f1b79d: btf_id_cmp_func (STB_LOCAL)
ffffffff81f38040-ffffffff81f3804d: btf_id_cmp_func (STB_LOCAL)
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
