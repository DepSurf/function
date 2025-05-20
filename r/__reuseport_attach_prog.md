# Function: <code>__reuseport_attach_prog</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __reuseport_attach_prog(struct bpf_prog *prog, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179d110)
Location: net/core/filter.c:1196
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff8179d110-ffffffff8179d191: __reuseport_attach_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __reuseport_attach_prog(struct bpf_prog *prog, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cabc0)
Location: net/core/filter.c:1198
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff817cabc0-ffffffff817cac41: __reuseport_attach_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __reuseport_attach_prog(struct bpf_prog *prog, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e9d40)
Location: net/core/filter.c:1223
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff817e9d40-ffffffff817e9dc1: __reuseport_attach_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __reuseport_attach_prog(struct bpf_prog *prog, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818653b0)
Location: net/core/filter.c:1244
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff818653b0-ffffffff81865431: __reuseport_attach_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __reuseport_attach_prog(struct bpf_prog *prog, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b2f50)
Location: net/core/filter.c:1456
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff818b2f50-ffffffff818b2fd1: __reuseport_attach_prog (STB_LOCAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
