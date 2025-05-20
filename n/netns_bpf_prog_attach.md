# Function: <code>netns_bpf_prog_attach</code>

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
int netns_bpf_prog_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff8122a960)
Location: kernel/bpf/net_namespace.c:200
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff8122a960-ffffffff8122aa6e: netns_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netns_bpf_prog_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81232720)
Location: kernel/bpf/net_namespace.c:296
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff81232720-ffffffff81232882: netns_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netns_bpf_prog_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff812368c0)
Location: kernel/bpf/net_namespace.c:296
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff812368c0-ffffffff81236a22: netns_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netns_bpf_prog_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81270ea0)
Location: kernel/bpf/net_namespace.c:296
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff81270ea0-ffffffff81271002: netns_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netns_bpf_prog_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff812bff90)
Location: kernel/bpf/net_namespace.c:297
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff812bff90-ffffffff812c00f5: netns_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netns_bpf_prog_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81323790)
Location: kernel/bpf/net_namespace.c:297
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff81323790-ffffffff813238f5: netns_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netns_bpf_prog_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff813539c0)
Location: kernel/bpf/net_namespace.c:297
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff813539c0-ffffffff81353b25: netns_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netns_bpf_prog_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff8137aeb0)
Location: kernel/bpf/net_namespace.c:297
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff8137aeb0-ffffffff8137b015: netns_bpf_prog_attach (STB_GLOBAL)
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
