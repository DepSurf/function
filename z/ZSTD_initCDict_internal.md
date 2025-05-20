# Function: <code>ZSTD_initCDict_internal</code>

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
size_t ZSTD_initCDict_internal(ZSTD_CDict *cdict, const void *dictBuffer, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType, ZSTD_CCtx_params params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81718f80)
Location: lib/zstd/compress/zstd_compress.c:3584
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
```
**Symbols:**

```
ffffffff81718f80-ffffffff81719187: ZSTD_initCDict_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_initCDict_internal(ZSTD_CDict *cdict, const void *dictBuffer, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType, ZSTD_CCtx_params params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180e600)
Location: lib/zstd/compress/zstd_compress.c:4669
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
```
**Symbols:**

```
ffffffff8180e600-ffffffff8180e7ee: ZSTD_initCDict_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_initCDict_internal(ZSTD_CDict *cdict, const void *dictBuffer, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType, ZSTD_CCtx_params params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184f110)
Location: lib/zstd/compress/zstd_compress.c:4669
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
```
**Symbols:**

```
ffffffff8184f110-ffffffff8184f2fe: ZSTD_initCDict_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_initCDict_internal(ZSTD_CDict *cdict, const void *dictBuffer, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType, ZSTD_CCtx_params params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a0cd0)
Location: lib/zstd/compress/zstd_compress.c:4669
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
```
**Symbols:**

```
ffffffff818a0cd0-ffffffff818a0ebe: ZSTD_initCDict_internal (STB_LOCAL)
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
