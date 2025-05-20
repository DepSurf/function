# Function: <code>netns_bpf_link_create</code>

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
int netns_bpf_link_create(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff8122ab60)
Location: kernel/bpf/net_namespace.c:359
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff8122ab60-ffffffff8122adcf: netns_bpf_link_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netns_bpf_link_create(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff812329a0)
Location: kernel/bpf/net_namespace.c:476
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff812329a0-ffffffff81232d27: netns_bpf_link_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netns_bpf_link_create(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81236b50)
Location: kernel/bpf/net_namespace.c:476
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff81236b50-ffffffff81236ed9: netns_bpf_link_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netns_bpf_link_create(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81271130)
Location: kernel/bpf/net_namespace.c:476
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff81271130-ffffffff812714b9: netns_bpf_link_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netns_bpf_link_create(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff812c0220)
Location: kernel/bpf/net_namespace.c:477
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff812c0220-ffffffff812c05cb: netns_bpf_link_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netns_bpf_link_create(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81323a50)
Location: kernel/bpf/net_namespace.c:477
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff81323a50-ffffffff81323dfc: netns_bpf_link_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netns_bpf_link_create(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81353c80)
Location: kernel/bpf/net_namespace.c:477
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff81353c80-ffffffff81354036: netns_bpf_link_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netns_bpf_link_create(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff8137b170)
Location: kernel/bpf/net_namespace.c:477
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff8137b170-ffffffff8137b555: netns_bpf_link_create (STB_GLOBAL)
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
