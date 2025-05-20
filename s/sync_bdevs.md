# Function: <code>sync_bdevs</code>

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
void sync_bdevs(bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166fb20)
Location: block/bdev.c:1023
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff8166fb20-ffffffff8166fc77: sync_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sync_bdevs(bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8172af40)
Location: block/bdev.c:1022
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff8172af40-ffffffff8172b09d: sync_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sync_bdevs(bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817671b0)
Location: block/bdev.c:984
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff817671b0-ffffffff81767310: sync_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sync_bdevs(bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a8e80)
Location: block/bdev.c:1067
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff817a8e80-ffffffff817a8fe0: sync_bdevs (STB_GLOBAL)
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
