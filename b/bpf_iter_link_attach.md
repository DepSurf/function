# Function: <code>bpf_iter_link_attach</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_iter_link_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81215e10)
Location: kernel/bpf/bpf_iter.c:382
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff81215e10-ffffffff81215f38: bpf_iter_link_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_iter_link_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81217ca0)
Location: kernel/bpf/bpf_iter.c:476
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff81217ca0-ffffffff81217e93: bpf_iter_link_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_iter_link_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff8121b100)
Location: kernel/bpf/bpf_iter.c:476
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff8121b100-ffffffff8121b2ed: bpf_iter_link_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_iter_link_attach(const union bpf_attr *attr, bpfptr_t uattr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81251f80)
Location: kernel/bpf/bpf_iter.c:498
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff81251f80-ffffffff812521d3: bpf_iter_link_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_iter_link_attach(const union bpf_attr *attr, bpfptr_t uattr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81299c40)
Location: kernel/bpf/bpf_iter.c:498
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff81299c40-ffffffff81299eab: bpf_iter_link_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_iter_link_attach(const union bpf_attr *attr, bpfptr_t uattr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_iter.c (0)
Location: kernel/bpf/bpf_iter.c:507
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff8206153f-ffffffff82061554: bpf_iter_link_attach.cold (STB_LOCAL)
ffffffff812f5ad0-ffffffff812f5d70: bpf_iter_link_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_iter_link_attach(const union bpf_attr *attr, bpfptr_t uattr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_iter.c (0)
Location: kernel/bpf/bpf_iter.c:507
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff820e0acc-ffffffff820e0ae1: bpf_iter_link_attach.cold (STB_LOCAL)
ffffffff81323870-ffffffff81323b10: bpf_iter_link_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_iter_link_attach(const union bpf_attr *attr, bpfptr_t uattr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_iter.c (0)
Location: kernel/bpf/bpf_iter.c:507
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff821bd28c-ffffffff821bd2a1: bpf_iter_link_attach.cold (STB_LOCAL)
ffffffff813477d0-ffffffff81347a9f: bpf_iter_link_attach (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bpfptr_t uattr</code>
</li>
<li>
<b>Param reordered. </b>
<code>attr, prog</code> ➡️ <code>attr, uattr, prog</code>
</li>
</ul>
</details>
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
