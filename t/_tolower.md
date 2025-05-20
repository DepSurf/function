# Function: <code>_tolower</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff813f27c4)
Location: include/linux/ctype.h:59
Inline: True
Inline callers:
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:vsscanf
```
```
In lib/kstrtox.c (ffffffff81401ce0)
Location: include/linux/ctype.h:59
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8143af66)
Location: include/linux/ctype.h:59
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
```
```
In lib/kstrtox.c (ffffffff81449790)
Location: include/linux/ctype.h:59
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81457f45)
Location: include/linux/ctype.h:62
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
```
```
In lib/kstrtox.c (ffffffff81468170)
Location: include/linux/ctype.h:62
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8146d7f4)
Location: include/linux/ctype.h:62
Inline: True
```
```
In lib/vsprintf.c (ffffffff818f98ad)
Location: include/linux/ctype.h:62
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81499b24)
Location: include/linux/ctype.h:63
Inline: True
```
```
In lib/vsprintf.c (ffffffff8198051d)
Location: include/linux/ctype.h:63
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814cedcf)
Location: include/linux/ctype.h:63
Inline: True
```
```
In lib/vsprintf.c (ffffffff819dc23f)
Location: include/linux/ctype.h:63
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814e36df)
Location: include/linux/ctype.h:63
Inline: True
```
```
In lib/vsprintf.c (ffffffff81a146b3)
Location: include/linux/ctype.h:63
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8150fabf)
Location: include/linux/ctype.h:63
Inline: True
```
```
In lib/vsprintf.c (ffffffff81a83fb6)
Location: include/linux/ctype.h:63
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8152d9bf)
Location: include/linux/ctype.h:63
Inline: True
```
```
In lib/vsprintf.c (ffffffff81abb226)
Location: include/linux/ctype.h:63
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815918ca)
Location: include/linux/ctype.h:63
Inline: True
Inline callers:
  - lib/kstrtox.c:_kstrtoull
```
```
In lib/vsprintf.c (ffffffff815f6d03)
Location: include/linux/ctype.h:63
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815ae40a)
Location: include/linux/ctype.h:70
Inline: True
Inline callers:
  - lib/kstrtox.c:_kstrtoull
```
```
In lib/vsprintf.c (ffffffff8161b123)
Location: include/linux/ctype.h:70
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815b8f01)
Location: include/linux/ctype.h:70
Inline: True
Inline callers:
  - lib/kstrtox.c:_kstrtoull
```
```
In lib/vsprintf.c (ffffffff815fc831)
Location: include/linux/ctype.h:70
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8161f751)
Location: include/linux/ctype.h:70
Inline: True
Inline callers:
  - lib/kstrtox.c:_kstrtoull
```
```
In lib/vsprintf.c (ffffffff8166a4c1)
Location: include/linux/ctype.h:70
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff816edac7)
Location: include/linux/ctype.h:70
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer_fixup_radix
  - lib/kstrtox.c:_parse_integer_fixup_radix
```
```
In lib/vsprintf.c (ffffffff81784386)
Location: include/linux/ctype.h:70
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff817de4f7)
Location: include/linux/ctype.h:70
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer_fixup_radix
  - lib/kstrtox.c:_parse_integer_fixup_radix
```
```
In lib/vsprintf.c (ffffffff82041356)
Location: include/linux/ctype.h:70
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8181dcd7)
Location: include/linux/ctype.h:70
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer_fixup_radix
  - lib/kstrtox.c:_parse_integer_fixup_radix
```
```
In lib/vsprintf.c (ffffffff820bf866)
Location: include/linux/ctype.h:70
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81863bf6)
Location: include/linux/ctype.h:70
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer_limit
  - lib/kstrtox.c:_parse_integer_fixup_radix
  - lib/kstrtox.c:_parse_integer_fixup_radix
```
```
In lib/vsprintf.c (ffffffff82199886)
Location: include/linux/ctype.h:70
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffff800010639d94)
Location: include/linux/ctype.h:63
Inline: True
```
```
In lib/vsprintf.c (ffff800010d98068)
Location: include/linux/ctype.h:63
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c07df6d4)
Location: include/linux/ctype.h:63
Inline: True
```
```
In lib/vsprintf.c (c0e9314c)
Location: include/linux/ctype.h:63
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c0000000007e09a4)
Location: include/linux/ctype.h:63
Inline: True
```
```
In lib/vsprintf.c (c000000000edb78c)
Location: include/linux/ctype.h:63
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffe000466692)
Location: include/linux/ctype.h:63
Inline: True
```
```
In lib/vsprintf.c (ffffffe0008bfbee)
Location: include/linux/ctype.h:63
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81525f9f)
Location: include/linux/ctype.h:63
Inline: True
```
```
In lib/vsprintf.c (ffffffff81a5a076)
Location: include/linux/ctype.h:63
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8151627f)
Location: include/linux/ctype.h:63
Inline: True
```
```
In lib/vsprintf.c (ffffffff81a17156)
Location: include/linux/ctype.h:63
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8152202f)
Location: include/linux/ctype.h:63
Inline: True
```
```
In lib/vsprintf.c (ffffffff81ac6466)
Location: include/linux/ctype.h:63
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8153b9af)
Location: include/linux/ctype.h:63
Inline: True
```
```
In lib/vsprintf.c (ffffffff81ad2946)
Location: include/linux/ctype.h:63
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
```
</details>
</li>
</ul>

## Differences
