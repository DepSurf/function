# Function: <code>sio_read_complete</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sio_read_complete(struct kiocb *iocb, long int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:385
Inline: False
Direct callers:
  - mm/page_io.c:__swap_read_unplug
```
**Symbols:**

```
ffffffff81378fd0-ffffffff81379168: sio_read_complete (STB_LOCAL)
ffffffff81e708bd-ffffffff81e708ce: sio_read_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sio_read_complete(struct kiocb *iocb, long int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff813f6970)
Location: mm/page_io.c:385
Inline: False
Direct callers:
  - mm/page_io.c:__swap_read_unplug
```
**Symbols:**

```
ffffffff813f6970-ffffffff813f6b14: sio_read_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sio_read_complete(struct kiocb *iocb, long int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81429800)
Location: mm/page_io.c:402
Inline: False
Direct callers:
  - mm/page_io.c:__swap_read_unplug
```
**Symbols:**

```
ffffffff81429800-ffffffff814299a4: sio_read_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sio_read_complete(struct kiocb *iocb, long int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff814632c0)
Location: mm/page_io.c:404
Inline: False
Direct callers:
  - mm/page_io.c:__swap_read_unplug
```
**Symbols:**

```
ffffffff814632c0-ffffffff81463425: sio_read_complete (STB_LOCAL)
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
