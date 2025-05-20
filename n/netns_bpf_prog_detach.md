# Function: <code>netns_bpf_prog_detach</code>

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
int netns_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff8122aa70)
Location: kernel/bpf/net_namespace.c:286
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_detach
```
**Symbols:**

```
ffffffff8122aa70-ffffffff8122ab55: netns_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netns_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81232890)
Location: kernel/bpf/net_namespace.c:382
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_detach
```
**Symbols:**

```
ffffffff81232890-ffffffff8123299c: netns_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netns_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81236a30)
Location: kernel/bpf/net_namespace.c:382
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff81236a30-ffffffff81236b43: netns_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netns_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81271010)
Location: kernel/bpf/net_namespace.c:382
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff81271010-ffffffff81271123: netns_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netns_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff812c0100)
Location: kernel/bpf/net_namespace.c:383
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff812c0100-ffffffff812c0220: netns_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netns_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81323910)
Location: kernel/bpf/net_namespace.c:383
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff81323910-ffffffff81323a37: netns_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netns_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81353b40)
Location: kernel/bpf/net_namespace.c:383
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff81353b40-ffffffff81353c70: netns_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netns_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff8137b030)
Location: kernel/bpf/net_namespace.c:383
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_detach
```
**Symbols:**

```
ffffffff8137b030-ffffffff8137b160: netns_bpf_prog_detach (STB_GLOBAL)
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
