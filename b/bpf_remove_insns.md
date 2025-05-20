# Function: <code>bpf_remove_insns</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d0f00)
Location: kernel/bpf/core.c:493
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff811d0f00-ffffffff811d0f7c: bpf_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dd490)
Location: kernel/bpf/core.c:493
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff811dd490-ffffffff811dd50c: bpf_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9eb0)
Location: kernel/bpf/core.c:493
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff811f9eb0-ffffffff811f9f2c: bpf_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f8ee0)
Location: kernel/bpf/core.c:489
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff811f8ee0-ffffffff811f8f5c: bpf_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9cc0)
Location: kernel/bpf/core.c:495
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff811f9cc0-ffffffff811f9d3c: bpf_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122b390)
Location: kernel/bpf/core.c:495
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff8122b390-ffffffff8122b40c: bpf_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126cdc0)
Location: kernel/bpf/core.c:507
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff8126cdc0-ffffffff8126ce59: bpf_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c1f00)
Location: kernel/bpf/core.c:515
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff812c1f00-ffffffff812c1f80: bpf_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e8dc0)
Location: kernel/bpf/core.c:516
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff812e8dc0-ffffffff812e8e40: bpf_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81307130)
Location: kernel/bpf/core.c:533
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff81307130-ffffffff813071b0: bpf_remove_insns (STB_GLOBAL)
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
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025e000)
Location: kernel/bpf/core.c:493
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffff80001025e000-ffff80001025e0a4: bpf_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c04916c8)
Location: kernel/bpf/core.c:493
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
c04916c8-c0491784: bpf_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000302c10)
Location: kernel/bpf/core.c:493
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
c000000000302c10-c000000000302cf4: bpf_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019c4be)
Location: kernel/bpf/core.c:493
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffe00019c4be-ffffffe00019c556: bpf_remove_insns (STB_GLOBAL)
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
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d5ab0)
Location: kernel/bpf/core.c:493
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff811d5ab0-ffffffff811d5b2c: bpf_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c8870)
Location: kernel/bpf/core.c:493
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff811c8870-ffffffff811c88ec: bpf_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d3880)
Location: kernel/bpf/core.c:493
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff811d3880-ffffffff811d38fc: bpf_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_remove_insns(struct bpf_prog *prog, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e1b70)
Location: kernel/bpf/core.c:493
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff811e1b70-ffffffff811e1bec: bpf_remove_insns (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
