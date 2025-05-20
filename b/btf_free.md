# Function: <code>btf_free</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void btf_free(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c6990)
Location: kernel/bpf/btf.c:668
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_free_rcu
```
**Symbols:**

```
ffffffff811c6990-ffffffff811c69cb: btf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void btf_free(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811d94b0)
Location: kernel/bpf/btf.c:796
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_free_rcu
```
**Symbols:**

```
ffffffff811d94b0-ffffffff811d94eb: btf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void btf_free(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ee090)
Location: kernel/bpf/btf.c:897
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_free_rcu
```
**Symbols:**

```
ffffffff811ee090-ffffffff811ee0d0: btf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void btf_free(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fa7a0)
Location: kernel/bpf/btf.c:897
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_free_rcu
```
**Symbols:**

```
ffffffff811fa7a0-ffffffff811fa7e0: btf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81225e67)
Location: kernel/bpf/btf.c:925
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_free_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122c8c9)
Location: kernel/bpf/btf.c:1511
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_free_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81231689)
Location: kernel/bpf/btf.c:1512
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_free_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8126a62a)
Location: kernel/bpf/btf.c:1512
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_free_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void btf_free(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812abdf0)
Location: kernel/bpf/btf.c:1638
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_free_rcu
```
**Symbols:**

```
ffffffff812abdf0-ffffffff812abe52: btf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void btf_free(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130b970)
Location: kernel/bpf/btf.c:1660
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_free_rcu
```
**Symbols:**

```
ffffffff8130b970-ffffffff8130ba2f: btf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void btf_free(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8133a9d0)
Location: kernel/bpf/btf.c:1690
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_free_rcu
```
**Symbols:**

```
ffffffff8133a9d0-ffffffff8133aa7d: btf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void btf_free(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81360b00)
Location: kernel/bpf/btf.c:1691
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_free_rcu
```
**Symbols:**

```
ffffffff81360b00-ffffffff81360bad: btf_free (STB_LOCAL)
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
void btf_free(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010280698)
Location: kernel/bpf/btf.c:897
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_free_rcu
```
**Symbols:**

```
ffff800010280698-ffff8000102806e4: btf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void btf_free(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b162c)
Location: kernel/bpf/btf.c:897
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_free_rcu
```
**Symbols:**

```
c04b162c-c04b1670: btf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void btf_free(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032aa10)
Location: kernel/bpf/btf.c:897
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_free_rcu
```
**Symbols:**

```
c00000000032aa10-c00000000032aa84: btf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void btf_free(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b6e18)
Location: kernel/bpf/btf.c:897
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_free_rcu
```
**Symbols:**

```
ffffffe0001b6e18-ffffffe0001b6e6a: btf_free (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void btf_free(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f2dc0)
Location: kernel/bpf/btf.c:897
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_free_rcu
```
**Symbols:**

```
ffffffff811f2dc0-ffffffff811f2e00: btf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void btf_free(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e5b10)
Location: kernel/bpf/btf.c:897
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_free_rcu
```
**Symbols:**

```
ffffffff811e5b10-ffffffff811e5b50: btf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void btf_free(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f0b90)
Location: kernel/bpf/btf.c:897
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_free_rcu
```
**Symbols:**

```
ffffffff811f0b90-ffffffff811f0bd0: btf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void btf_free(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ff0a0)
Location: kernel/bpf/btf.c:897
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_free_rcu
```
**Symbols:**

```
ffffffff811ff0a0-ffffffff811ff0e0: btf_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
