# Function: <code>crc64_rocksoft_update</code>

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
u64 crc64_rocksoft_update(u64 crc, const unsigned char *buffer, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc64-rocksoft.c (ffffffff816fa070)
Location: lib/crc64-rocksoft.c:57
Inline: False
Direct callers:
  - lib/crc64-rocksoft.c:crc64_rocksoft
```
**Symbols:**

```
ffffffff816fa070-ffffffff816fa10a: crc64_rocksoft_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 crc64_rocksoft_update(u64 crc, const unsigned char *buffer, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc64-rocksoft.c (ffffffff817eca70)
Location: lib/crc64-rocksoft.c:57
Inline: False
Direct callers:
  - lib/crc64-rocksoft.c:crc64_rocksoft
```
**Symbols:**

```
ffffffff817eca70-ffffffff817ecb0a: crc64_rocksoft_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 crc64_rocksoft_update(u64 crc, const unsigned char *buffer, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crc64-rocksoft.c (ffffffff8182cef0)
Location: lib/crc64-rocksoft.c:57
Inline: True
Inline callers:
  - lib/crc64-rocksoft.c:crc64_rocksoft
```
**Symbols:**

```
ffffffff8182cc50-ffffffff8182ccea: crc64_rocksoft_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u64 crc64_rocksoft_update(u64 crc, const unsigned char *buffer, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crc64-rocksoft.c (ffffffff8187ea80)
Location: lib/crc64-rocksoft.c:57
Inline: True
Inline callers:
  - lib/crc64-rocksoft.c:crc64_rocksoft
```
**Symbols:**

```
ffffffff8187e7e0-ffffffff8187e87a: crc64_rocksoft_update (STB_GLOBAL)
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
