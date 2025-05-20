# Function: <code>ZSTD_insertAndFindFirstIndexHash3</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b4ad5)
Location: lib/zstd/zstd_opt.h:215
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815da40d)
Location: lib/zstd/zstd_opt.h:215
Inline: True
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff81746a92)
Location: lib/zstd/compress/zstd_opt.c:353
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
U32 ZSTD_insertAndFindFirstIndexHash3(const ZSTD_matchState_t *ms, U32 *nextToUpdate3, const const BYTE * ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (0)
Location: lib/zstd/compress/zstd_opt.c:382
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3
```
**Symbols:**

```
ffffffff8185e650-ffffffff8185e6ee: ZSTD_insertAndFindFirstIndexHash3 (STB_LOCAL)
ffffffff8208a540-ffffffff8208a5a8: ZSTD_insertAndFindFirstIndexHash3.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
U32 ZSTD_insertAndFindFirstIndexHash3(const ZSTD_matchState_t *ms, U32 *nextToUpdate3, const const BYTE * ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (0)
Location: lib/zstd/compress/zstd_opt.c:382
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3
```
**Symbols:**

```
ffffffff8189f200-ffffffff8189f29e: ZSTD_insertAndFindFirstIndexHash3 (STB_LOCAL)
ffffffff8210a997-ffffffff8210a9ff: ZSTD_insertAndFindFirstIndexHash3.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
U32 ZSTD_insertAndFindFirstIndexHash3(const ZSTD_matchState_t *ms, U32 *nextToUpdate3, const const BYTE * ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (0)
Location: lib/zstd/compress/zstd_opt.c:382
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3
```
**Symbols:**

```
ffffffff818f0dc0-ffffffff818f0e5e: ZSTD_insertAndFindFirstIndexHash3 (STB_LOCAL)
ffffffff821e8b04-ffffffff821e8b6c: ZSTD_insertAndFindFirstIndexHash3.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
