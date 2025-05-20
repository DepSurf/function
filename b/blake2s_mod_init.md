# Function: <code>blake2s_mod_init</code>

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
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int blake2s_mod_init();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/blake2s-glue.c (ffffffff83477b5f)
Location: arch/x86/crypto/blake2s-glue.c:58
Inline: False
```
```
In lib/crypto/blake2s.c (ffffffff834a032a)
Location: lib/crypto/blake2s.c:61
Inline: False
```
**Symbols:**

```
ffffffff83477b5f-ffffffff83477bde: blake2s_mod_init (STB_LOCAL)
ffffffff834a032a-ffffffff834a033b: blake2s_mod_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int blake2s_mod_init();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/blake2s-glue.c (ffffffff83ea13c0)
Location: arch/x86/crypto/blake2s-glue.c:58
Inline: False
```
```
In lib/crypto/blake2s.c (ffffffff83ed9130)
Location: lib/crypto/blake2s.c:61
Inline: False
```
**Symbols:**

```
ffffffff83ea13c0-ffffffff83ea1443: blake2s_mod_init (STB_LOCAL)
ffffffff83ed9130-ffffffff83ed9141: blake2s_mod_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int blake2s_mod_init();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/blake2s-glue.c (ffffffff836c5610)
Location: arch/x86/crypto/blake2s-glue.c:57
Inline: False
```
```
In lib/crypto/blake2s.c (ffffffff836feba0)
Location: lib/crypto/blake2s.c:61
Inline: False
```
**Symbols:**

```
ffffffff836c5610-ffffffff836c5693: blake2s_mod_init (STB_LOCAL)
ffffffff836feba0-ffffffff836febb1: blake2s_mod_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int blake2s_mod_init();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/blake2s-glue.c (ffffffff838f6210)
Location: arch/x86/crypto/blake2s-glue.c:57
Inline: False
```
```
In lib/crypto/blake2s.c (ffffffff83932400)
Location: lib/crypto/blake2s.c:61
Inline: False
```
**Symbols:**

```
ffffffff838f6210-ffffffff838f6293: blake2s_mod_init (STB_LOCAL)
ffffffff83932400-ffffffff83932411: blake2s_mod_init (STB_LOCAL)
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
