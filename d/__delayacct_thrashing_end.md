# Function: <code>__delayacct_thrashing_end</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __delayacct_thrashing_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8117be50)
Location: kernel/delayacct.c:180
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
**Symbols:**

```
ffffffff8117be50-ffffffff8117be7c: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __delayacct_thrashing_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff81188c70)
Location: kernel/delayacct.c:171
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
**Symbols:**

```
ffffffff81188c70-ffffffff81188c9c: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __delayacct_thrashing_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff81194bb0)
Location: kernel/delayacct.c:171
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
**Symbols:**

```
ffffffff81194bb0-ffffffff81194bdc: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __delayacct_thrashing_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff811a9c40)
Location: kernel/delayacct.c:171
Inline: False
Direct callers:
  - mm/filemap.c:wait_on_page_bit_common
```
**Symbols:**

```
ffffffff811a9c40-ffffffff811a9c91: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __delayacct_thrashing_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff811a7260)
Location: kernel/delayacct.c:171
Inline: False
Direct callers:
  - mm/filemap.c:wait_on_page_bit_common
```
**Symbols:**

```
ffffffff811a7260-ffffffff811a72b1: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __delayacct_thrashing_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff811a7da0)
Location: kernel/delayacct.c:171
Inline: False
Direct callers:
  - mm/filemap.c:wait_on_page_bit_common
```
**Symbols:**

```
ffffffff811a7da0-ffffffff811a7df1: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __delayacct_thrashing_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff811d18d0)
Location: kernel/delayacct.c:206
Inline: False
Direct callers:
  - mm/filemap.c:wait_on_page_bit_common
```
**Symbols:**

```
ffffffff811d18d0-ffffffff811d1928: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __delayacct_thrashing_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff81205f20)
Location: kernel/delayacct.c:222
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:migration_entry_wait_on_locked
```
**Symbols:**

```
ffffffff81205f20-ffffffff81205f7e: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __delayacct_thrashing_end(bool *in_thrashing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/delayacct.c (0)
Location: kernel/delayacct.c:227
Inline: False
Direct callers:
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/page_io.c:swap_readpage
```
**Symbols:**

```
ffffffff8205ca34-ffffffff8205ca48: __delayacct_thrashing_end.cold (STB_LOCAL)
ffffffff8124e160-ffffffff8124e1e5: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __delayacct_thrashing_end(bool *in_thrashing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/delayacct.c (0)
Location: kernel/delayacct.c:230
Inline: False
Direct callers:
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/page_io.c:swap_readpage
```
**Symbols:**

```
ffffffff820db3d5-ffffffff820db3e9: __delayacct_thrashing_end.cold (STB_LOCAL)
ffffffff812654e0-ffffffff8126555e: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __delayacct_thrashing_end(bool *in_thrashing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/delayacct.c (0)
Location: kernel/delayacct.c:230
Inline: False
Direct callers:
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/page_io.c:swap_read_folio
```
**Symbols:**

```
ffffffff821b70f6-ffffffff821b710a: __delayacct_thrashing_end.cold (STB_LOCAL)
ffffffff8127f360-ffffffff8127f3de: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __delayacct_thrashing_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffff80001020cd50)
Location: kernel/delayacct.c:171
Inline: False
Direct callers:
  - mm/filemap.c:wait_on_page_bit_common
```
**Symbols:**

```
ffff80001020cd50-ffff80001020cd80: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __delayacct_thrashing_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (c044b7a0)
Location: kernel/delayacct.c:171
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
**Symbols:**

```
c044b7a0-c044b7dc: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __delayacct_thrashing_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (c00000000028aa10)
Location: kernel/delayacct.c:171
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
**Symbols:**

```
c00000000028aa10-c00000000028aa38: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __delayacct_thrashing_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffe00016dfa0)
Location: kernel/delayacct.c:171
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
**Symbols:**

```
ffffffe00016dfa0-ffffffe00016dfd6: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __delayacct_thrashing_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8118d1d0)
Location: kernel/delayacct.c:171
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
**Symbols:**

```
ffffffff8118d1d0-ffffffff8118d1fc: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __delayacct_thrashing_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff811802f0)
Location: kernel/delayacct.c:171
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
**Symbols:**

```
ffffffff811802f0-ffffffff8118031c: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __delayacct_thrashing_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8118afa0)
Location: kernel/delayacct.c:171
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
**Symbols:**

```
ffffffff8118afa0-ffffffff8118afcc: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __delayacct_thrashing_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff81198910)
Location: kernel/delayacct.c:171
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
**Symbols:**

```
ffffffff81198910-ffffffff8119893c: __delayacct_thrashing_end (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *in_thrashing</code>
</li>
</ul>
</details>
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
