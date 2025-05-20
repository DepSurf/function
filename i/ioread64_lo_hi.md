# Function: <code>ioread64_lo_hi</code>

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
u64 ioread64_lo_hi(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81510b10)
Location: lib/iomap.c:145
Inline: False
```
**Symbols:**

```
ffffffff81510b10-ffffffff81510b51: ioread64_lo_hi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 ioread64_lo_hi(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81531580)
Location: lib/iomap.c:145
Inline: False
```
**Symbols:**

```
ffffffff81531580-ffffffff815315c1: ioread64_lo_hi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 ioread64_lo_hi(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81595970)
Location: lib/iomap.c:145
Inline: False
```
**Symbols:**

```
ffffffff81595970-ffffffff815959dd: ioread64_lo_hi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 ioread64_lo_hi(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815b1400)
Location: lib/iomap.c:145
Inline: False
```
**Symbols:**

```
ffffffff815b1400-ffffffff815b146d: ioread64_lo_hi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 ioread64_lo_hi(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815bc210)
Location: lib/iomap.c:145
Inline: False
```
**Symbols:**

```
ffffffff815bc210-ffffffff815bc27d: ioread64_lo_hi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 ioread64_lo_hi(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81623060)
Location: lib/iomap.c:145
Inline: False
```
**Symbols:**

```
ffffffff81623060-ffffffff816230cd: ioread64_lo_hi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 ioread64_lo_hi(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816f2f00)
Location: lib/iomap.c:145
Inline: False
```
**Symbols:**

```
ffffffff816f2f00-ffffffff816f2f97: ioread64_lo_hi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 ioread64_lo_hi(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff817e4dd0)
Location: lib/iomap.c:156
Inline: False
```
**Symbols:**

```
ffffffff817e4dd0-ffffffff817e4e67: ioread64_lo_hi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 ioread64_lo_hi(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81824e10)
Location: lib/iomap.c:156
Inline: False
```
**Symbols:**

```
ffffffff81824e10-ffffffff81824ea7: ioread64_lo_hi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 ioread64_lo_hi(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81876820)
Location: lib/iomap.c:156
Inline: False
```
**Symbols:**

```
ffffffff81876820-ffffffff818768b7: ioread64_lo_hi (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u64 ioread64_lo_hi(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iomap.c (c0000000007e66c0)
Location: lib/iomap.c:145
Inline: True
```
**Symbols:**

```
c0000000007e66c0-c0000000007e68cc: ioread64_lo_hi (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
u64 ioread64_lo_hi(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81529b60)
Location: lib/iomap.c:145
Inline: False
```
**Symbols:**

```
ffffffff81529b60-ffffffff81529ba1: ioread64_lo_hi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 ioread64_lo_hi(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81519e40)
Location: lib/iomap.c:145
Inline: False
```
**Symbols:**

```
ffffffff81519e40-ffffffff81519e81: ioread64_lo_hi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 ioread64_lo_hi(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81525bf0)
Location: lib/iomap.c:145
Inline: False
```
**Symbols:**

```
ffffffff81525bf0-ffffffff81525c31: ioread64_lo_hi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 ioread64_lo_hi(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8153f570)
Location: lib/iomap.c:145
Inline: False
```
**Symbols:**

```
ffffffff8153f570-ffffffff8153f5b1: ioread64_lo_hi (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *addr</code> ➡️ <code>const void *addr</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
