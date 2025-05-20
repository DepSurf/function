# Function: <code>_parse_integer_fixup_radix</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81401c10)
Location: lib/kstrtox.c:23
Inline: True
Direct callers:
  - lib/vsprintf.c:simple_strtoull
  - lib/vsprintf.c:vsscanf
  - lib/kstrtox.c:_kstrtoull
```
**Symbols:**

```
ffffffff81401c10-ffffffff81401c71: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814496d0)
Location: lib/kstrtox.c:23
Inline: True
Direct callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoull
  - lib/kstrtox.c:_kstrtoull
```
**Symbols:**

```
ffffffff814496d0-ffffffff81449730: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814680c0)
Location: lib/kstrtox.c:23
Inline: True
Direct callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoull
  - lib/kstrtox.c:_kstrtoull
```
**Symbols:**

```
ffffffff814680c0-ffffffff81468120: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8146d7d0)
Location: lib/kstrtox.c:23
Inline: True
Direct callers:
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffff8146d7d0-ffffffff8146d830: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81499b00)
Location: lib/kstrtox.c:24
Inline: True
Direct callers:
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffff81499b00-ffffffff81499b60: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814cedb0)
Location: lib/kstrtox.c:24
Inline: True
Direct callers:
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffff814cedb0-ffffffff814cee09: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814e36c0)
Location: lib/kstrtox.c:24
Inline: True
Direct callers:
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffff814e36c0-ffffffff814e3719: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8150faa0)
Location: lib/kstrtox.c:24
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffff8150faa0-ffffffff8150faf9: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8152d9a0)
Location: lib/kstrtox.c:24
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffff8152d9a0-ffffffff8152d9f9: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81591850)
Location: lib/kstrtox.c:24
Inline: True
Inline callers:
  - lib/kstrtox.c:_kstrtoull
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff81591740-ffffffff81591799: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815ae390)
Location: lib/kstrtox.c:24
Inline: True
Inline callers:
  - lib/kstrtox.c:_kstrtoull
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff815ae280-ffffffff815ae2d9: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815b8df0)
Location: lib/kstrtox.c:24
Inline: True
Inline callers:
  - lib/kstrtox.c:_kstrtoull
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/vsprintf.c:simple_strtoll
```
**Symbols:**

```
ffffffff815b9bb0-ffffffff815b9c09: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8161f640)
Location: lib/kstrtox.c:25
Inline: True
Inline callers:
  - lib/kstrtox.c:_kstrtoull
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/vsprintf.c:simple_strtoll
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffff81620500-ffffffff81620559: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff816edaa0)
Location: lib/kstrtox.c:26
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:simple_strntoull
```
**Symbols:**

```
ffffffff816edaa0-ffffffff816edb11: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff817de4d0)
Location: lib/kstrtox.c:26
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:simple_strntoull
```
**Symbols:**

```
ffffffff817de4d0-ffffffff817de541: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8181dcb0)
Location: lib/kstrtox.c:26
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:simple_strntoull
```
**Symbols:**

```
ffffffff8181dcb0-ffffffff8181dd21: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81863b20)
Location: lib/kstrtox.c:26
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:simple_strntoull
```
**Symbols:**

```
ffffffff81863b20-ffffffff81863b91: _parse_integer_fixup_radix (STB_GLOBAL)
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
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffff800010639d60)
Location: lib/kstrtox.c:24
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffff800010639d60-ffff800010639df0: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c07df690)
Location: lib/kstrtox.c:24
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
c07df690-c07df728: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c0000000007e0960)
Location: lib/kstrtox.c:24
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
c0000000007e0960-c0000000007e0a04: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffe000466660)
Location: lib/kstrtox.c:24
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffe000466660-ffffffe0004666de: _parse_integer_fixup_radix (STB_GLOBAL)
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
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81525f80)
Location: lib/kstrtox.c:24
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffff81525f80-ffffffff81525fd9: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81516260)
Location: lib/kstrtox.c:24
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffff81516260-ffffffff815162b9: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81522010)
Location: lib/kstrtox.c:24
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffff81522010-ffffffff81522069: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *_parse_integer_fixup_radix(const char *s, unsigned int *base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8153b990)
Location: lib/kstrtox.c:24
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:__bpf_strtoull
  - lib/kstrtox.c:_kstrtoull
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffff8153b990-ffffffff8153b9e9: _parse_integer_fixup_radix (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
