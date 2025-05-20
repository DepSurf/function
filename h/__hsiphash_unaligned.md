# Function: <code>__hsiphash_unaligned</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 __hsiphash_unaligned(const void *data, size_t len, const hsiphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81668260)
Location: lib/siphash.c:286
Inline: False
```
**Symbols:**

```
ffffffff81668260-ffffffff816683ef: __hsiphash_unaligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 __hsiphash_unaligned(const void *data, size_t len, const hsiphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff817819b0)
Location: lib/siphash.c:279
Inline: False
```
**Symbols:**

```
ffffffff817819b0-ffffffff81781b8a: __hsiphash_unaligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 __hsiphash_unaligned(const void *data, size_t len, const hsiphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff8203e0f0)
Location: lib/siphash.c:279
Inline: False
```
**Symbols:**

```
ffffffff8203e0f0-ffffffff8203e2a2: __hsiphash_unaligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 __hsiphash_unaligned(const void *data, size_t len, const hsiphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff820bc5f0)
Location: lib/siphash.c:279
Inline: False
```
**Symbols:**

```
ffffffff820bc5f0-ffffffff820bc7a2: __hsiphash_unaligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 __hsiphash_unaligned(const void *data, size_t len, const hsiphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff82196ef0)
Location: lib/siphash.c:279
Inline: False
```
**Symbols:**

```
ffffffff82196ef0-ffffffff821970a2: __hsiphash_unaligned (STB_GLOBAL)
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
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 __hsiphash_unaligned(const void *data, size_t len, const hsiphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffe0008bbec0)
Location: lib/siphash.c:285
Inline: False
```
**Symbols:**

```
ffffffe0008bbec0-ffffffe0008bc16a: __hsiphash_unaligned (STB_GLOBAL)
```
</details>
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
</ul>
