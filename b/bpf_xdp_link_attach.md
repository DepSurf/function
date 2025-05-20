# Function: <code>bpf_xdp_link_attach</code>

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
int bpf_xdp_link_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0dd20)
Location: net/core/dev.c:9409
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff81a0dd20-ffffffff81a0deb2: bpf_xdp_link_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_xdp_link_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f4a30)
Location: net/core/dev.c:9668
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff819f4a30-ffffffff819f4bd2: bpf_xdp_link_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_xdp_link_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa6360)
Location: net/core/dev.c:9675
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff81aa6360-ffffffff81aa6502: bpf_xdp_link_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_xdp_link_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1e0f0)
Location: net/core/dev.c:9413
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff81c1e0f0-ffffffff81c1e2b5: bpf_xdp_link_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_xdp_link_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcf530)
Location: net/core/dev.c:9400
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff81dcf530-ffffffff81dcf6f5: bpf_xdp_link_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_xdp_link_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e40140)
Location: net/core/dev.c:9412
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff81e40140-ffffffff81e40305: bpf_xdp_link_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_xdp_link_attach(const union bpf_attr *attr, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efeaa0)
Location: net/core/dev.c:9530
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
```
**Symbols:**

```
ffffffff81efeaa0-ffffffff81efed0b: bpf_xdp_link_attach (STB_GLOBAL)
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
