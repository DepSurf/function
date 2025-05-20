# Function: <code>netns_bpf_prog_query</code>

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
int netns_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff8122a7f0)
Location: kernel/bpf/net_namespace.c:174
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_query
```
**Symbols:**

```
ffffffff8122a7f0-ffffffff8122a952: netns_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netns_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81232590)
Location: kernel/bpf/net_namespace.c:270
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_query
```
**Symbols:**

```
ffffffff81232590-ffffffff81232715: netns_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netns_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81236730)
Location: kernel/bpf/net_namespace.c:270
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff81236730-ffffffff812368b6: netns_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netns_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81270d10)
Location: kernel/bpf/net_namespace.c:270
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff81270d10-ffffffff81270e96: netns_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netns_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff812bfe00)
Location: kernel/bpf/net_namespace.c:271
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff812bfe00-ffffffff812bff8f: netns_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netns_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff813235f0)
Location: kernel/bpf/net_namespace.c:271
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff813235f0-ffffffff8132377f: netns_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netns_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81353820)
Location: kernel/bpf/net_namespace.c:271
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff81353820-ffffffff813539af: netns_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netns_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff8137ad10)
Location: kernel/bpf/net_namespace.c:271
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_query
```
**Symbols:**

```
ffffffff8137ad10-ffffffff8137ae9f: netns_bpf_prog_query (STB_GLOBAL)
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
