# Function: <code>bpf_prog_kallsyms_del</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118f280)
Location: kernel/bpf/core.c:404
Inline: False
```
**Symbols:**

```
ffffffff8118f280-ffffffff8118f31d: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119d6f0)
Location: kernel/bpf/core.c:413
Inline: False
```
**Symbols:**

```
ffffffff8119d6f0-ffffffff8119d78d: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b1e30)
Location: kernel/bpf/core.c:492
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_subprogs
```
**Symbols:**

```
ffffffff811b1e30-ffffffff811b1ec7: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c06e0)
Location: kernel/bpf/core.c:615
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_subprogs
```
**Symbols:**

```
ffffffff811c06e0-ffffffff811c0777: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d1220)
Location: kernel/bpf/core.c:657
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_subprogs
```
**Symbols:**

```
ffffffff811d1220-ffffffff811d12b6: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dd7b0)
Location: kernel/bpf/core.c:657
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffff811dd7b0-ffffffff811dd846: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa157)
Location: kernel/bpf/core.c:659
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffff811fa250-ffffffff811fa279: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f918a)
Location: kernel/bpf/core.c:655
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffff811f9280-ffffffff811f92a9: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9f6a)
Location: kernel/bpf/core.c:661
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffff811fa110-ffffffff811fa139: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122b63a)
Location: kernel/bpf/core.c:662
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffff8122b7e0-ffffffff8122b809: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126d0aa)
Location: kernel/bpf/core.c:665
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffff8126d270-ffffffff8126d2a9: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c21fa)
Location: kernel/bpf/core.c:673
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffff812c23e0-ffffffff812c2419: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e90ba)
Location: kernel/bpf/core.c:674
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffff812e92a0-ffffffff812e92d9: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8130742a)
Location: kernel/bpf/core.c:712
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffff81307620-ffffffff81307659: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025e3e8)
Location: kernel/bpf/core.c:657
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffff80001025e3e8-ffff80001025e51c: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0491b7c)
Location: kernel/bpf/core.c:657
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
c0491b7c-c0491c38: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000303140)
Location: kernel/bpf/core.c:657
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
c000000000303140-c00000000030325c: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019c830)
Location: kernel/bpf/core.c:657
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffe00019c830-ffffffe00019c8ee: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d5dd0)
Location: kernel/bpf/core.c:657
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffff811d5dd0-ffffffff811d5e66: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c8b90)
Location: kernel/bpf/core.c:657
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffff811c8b90-ffffffff811c8c26: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d3ba0)
Location: kernel/bpf/core.c:657
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffff811d3ba0-ffffffff811d3c36: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_kallsyms_del(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e1e90)
Location: kernel/bpf/core.c:657
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffff811e1e90-ffffffff811e1f26: bpf_prog_kallsyms_del (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
