# Function: <code>blake2s_compress_ssse3</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blake2s_compress_ssse3();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/blake2s-core.S (ffffffff810b9be0)
Location: arch/x86/crypto/blake2s-core.S
Inline: False
Direct callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
```
**Symbols:**

```
ffffffff810b9be0-ffffffff810b9e24: blake2s_compress_ssse3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blake2s_compress_ssse3();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/blake2s-core.S (ffffffff810d58f0)
Location: arch/x86/crypto/blake2s-core.S
Inline: False
Direct callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
```
**Symbols:**

```
ffffffff810d58f0-ffffffff810d5b44: blake2s_compress_ssse3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blake2s_compress_ssse3();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/blake2s-core.S (ffffffff810e0e30)
Location: arch/x86/crypto/blake2s-core.S
Inline: False
Direct callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
```
**Symbols:**

```
ffffffff810e0e30-ffffffff810e1084: blake2s_compress_ssse3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blake2s_compress_ssse3();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/blake2s-core.S (ffffffff810e96b0)
Location: arch/x86/crypto/blake2s-core.S
Inline: False
Direct callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
```
**Symbols:**

```
ffffffff810e96b0-ffffffff810e9904: blake2s_compress_ssse3 (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
