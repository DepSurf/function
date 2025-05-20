# Function: <code>ZSTD_optLdm_skipRawSeqStoreBytes</code>

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
void ZSTD_optLdm_skipRawSeqStoreBytes(rawSeqStore_t *rawSeqStore, size_t nbBytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff817444b0)
Location: lib/zstd/compress/zstd_opt.c:795
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_opt_getNextMatchAndUpdateSeqStore
  - lib/zstd/compress/zstd_opt.c:ZSTD_opt_getNextMatchAndUpdateSeqStore
  - lib/zstd/compress/zstd_opt.c:ZSTD_opt_getNextMatchAndUpdateSeqStore
```
**Symbols:**

```
ffffffff817444b0-ffffffff81744537: ZSTD_optLdm_skipRawSeqStoreBytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ZSTD_optLdm_skipRawSeqStoreBytes(rawSeqStore_t *rawSeqStore, size_t nbBytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff8185df50)
Location: lib/zstd/compress/zstd_opt.c:881
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_opt_getNextMatchAndUpdateSeqStore
  - lib/zstd/compress/zstd_opt.c:ZSTD_opt_getNextMatchAndUpdateSeqStore
  - lib/zstd/compress/zstd_opt.c:ZSTD_opt_getNextMatchAndUpdateSeqStore
```
**Symbols:**

```
ffffffff8185df50-ffffffff8185dfd7: ZSTD_optLdm_skipRawSeqStoreBytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ZSTD_optLdm_skipRawSeqStoreBytes(rawSeqStore_t *rawSeqStore, size_t nbBytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff8189eb00)
Location: lib/zstd/compress/zstd_opt.c:881
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_opt_getNextMatchAndUpdateSeqStore
  - lib/zstd/compress/zstd_opt.c:ZSTD_opt_getNextMatchAndUpdateSeqStore
  - lib/zstd/compress/zstd_opt.c:ZSTD_opt_getNextMatchAndUpdateSeqStore
```
**Symbols:**

```
ffffffff8189eb00-ffffffff8189eb87: ZSTD_optLdm_skipRawSeqStoreBytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ZSTD_optLdm_skipRawSeqStoreBytes(rawSeqStore_t *rawSeqStore, size_t nbBytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff818f06c0)
Location: lib/zstd/compress/zstd_opt.c:881
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_opt_getNextMatchAndUpdateSeqStore
  - lib/zstd/compress/zstd_opt.c:ZSTD_opt_getNextMatchAndUpdateSeqStore
  - lib/zstd/compress/zstd_opt.c:ZSTD_opt_getNextMatchAndUpdateSeqStore
```
**Symbols:**

```
ffffffff818f06c0-ffffffff818f0747: ZSTD_optLdm_skipRawSeqStoreBytes (STB_LOCAL)
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
