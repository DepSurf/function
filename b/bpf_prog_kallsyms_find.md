# Function: <code>bpf_prog_kallsyms_find</code>

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
struct bpf_prog *bpf_prog_kallsyms_find(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118ded0)
Location: kernel/bpf/core.c:414
Inline: False
Direct callers:
  - kernel/bpf/core.c:is_bpf_text_address
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
ffffffff8118ded0-ffffffff8118df75: bpf_prog_kallsyms_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_kallsyms_find(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119c180)
Location: kernel/bpf/core.c:423
Inline: False
Direct callers:
  - kernel/bpf/core.c:is_bpf_text_address
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
ffffffff8119c180-ffffffff8119c228: bpf_prog_kallsyms_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_kallsyms_find(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b1260)
Location: kernel/bpf/core.c:502
Inline: True
Direct callers:
  - kernel/bpf/core.c:is_bpf_text_address
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
ffffffff811b1260-ffffffff811b1307: bpf_prog_kallsyms_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_kallsyms_find(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811bf8e0)
Location: kernel/bpf/core.c:625
Inline: True
Direct callers:
  - kernel/bpf/core.c:is_bpf_text_address
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
ffffffff811bf8e0-ffffffff811bf987: bpf_prog_kallsyms_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_kallsyms_find(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811cfea0)
Location: kernel/bpf/core.c:667
Inline: True
Direct callers:
  - kernel/bpf/core.c:is_bpf_text_address
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
ffffffff811cfea0-ffffffff811cff4c: bpf_prog_kallsyms_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_kallsyms_find(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dc450)
Location: kernel/bpf/core.c:667
Inline: True
Direct callers:
  - kernel/bpf/core.c:is_bpf_text_address
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
ffffffff811dc450-ffffffff811dc4fc: bpf_prog_kallsyms_find (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_kallsyms_find(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025c4f8)
Location: kernel/bpf/core.c:667
Inline: True
Direct callers:
  - kernel/bpf/core.c:is_bpf_text_address
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
ffff80001025c4f8-ffff80001025c5e0: bpf_prog_kallsyms_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_kallsyms_find(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0490588)
Location: kernel/bpf/core.c:667
Inline: True
Direct callers:
  - kernel/bpf/core.c:is_bpf_text_address
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
c0490588-c04906cc: bpf_prog_kallsyms_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_kallsyms_find(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000301510)
Location: kernel/bpf/core.c:667
Inline: True
Direct callers:
  - kernel/bpf/core.c:is_bpf_text_address
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
c000000000301510-c000000000301618: bpf_prog_kallsyms_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_kallsyms_find(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019b5f2)
Location: kernel/bpf/core.c:667
Inline: True
Direct callers:
  - kernel/bpf/core.c:is_bpf_text_address
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
ffffffe00019b5f2-ffffffe00019b6aa: bpf_prog_kallsyms_find (STB_LOCAL)
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
struct bpf_prog *bpf_prog_kallsyms_find(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d4a70)
Location: kernel/bpf/core.c:667
Inline: True
Direct callers:
  - kernel/bpf/core.c:is_bpf_text_address
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
ffffffff811d4a70-ffffffff811d4b1c: bpf_prog_kallsyms_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_kallsyms_find(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c7830)
Location: kernel/bpf/core.c:667
Inline: True
Direct callers:
  - kernel/bpf/core.c:is_bpf_text_address
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
ffffffff811c7830-ffffffff811c78dc: bpf_prog_kallsyms_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_kallsyms_find(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d2840)
Location: kernel/bpf/core.c:667
Inline: True
Direct callers:
  - kernel/bpf/core.c:is_bpf_text_address
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
ffffffff811d2840-ffffffff811d28ec: bpf_prog_kallsyms_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_kallsyms_find(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e0b30)
Location: kernel/bpf/core.c:667
Inline: True
Direct callers:
  - kernel/bpf/core.c:is_bpf_text_address
  - kernel/bpf/core.c:__bpf_address_lookup
```
**Symbols:**

```
ffffffff811e0b30-ffffffff811e0bdc: bpf_prog_kallsyms_find (STB_LOCAL)
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
