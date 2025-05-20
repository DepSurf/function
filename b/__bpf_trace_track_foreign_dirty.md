# Function: <code>__bpf_trace_track_foreign_dirty</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130f390)
Location: include/trace/events/writeback.h:238
Inline: False
```
**Symbols:**

```
ffffffff8130f390-ffffffff8130f39b: __bpf_trace_track_foreign_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (0)
Location: include/trace/events/writeback.h:237
Inline: False
```
**Symbols:**

```
ffffffff81348e60-ffffffff81348e6b: __bpf_trace_track_foreign_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (0)
Location: include/trace/events/writeback.h:236
Inline: False
```
**Symbols:**

```
ffffffff81355dc0-ffffffff81355dcb: __bpf_trace_track_foreign_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (0)
Location: include/trace/events/writeback.h:236
Inline: False
```
**Symbols:**

```
ffffffff8135c9a0-ffffffff8135c9ab: __bpf_trace_track_foreign_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (0)
Location: include/trace/events/writeback.h:237
Inline: False
```
**Symbols:**

```
ffffffff813aadf0-ffffffff813aadfb: __bpf_trace_track_foreign_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_track_foreign_dirty(void *__data, struct folio *folio, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (0)
Location: include/trace/events/writeback.h:237
Inline: False
```
**Symbols:**

```
ffffffff81431cb0-ffffffff81431cc5: __bpf_trace_track_foreign_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_track_foreign_dirty(void *__data, struct folio *folio, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (0)
Location: include/trace/events/writeback.h:237
Inline: False
```
**Symbols:**

```
ffffffff814bfe30-ffffffff814bfe45: __bpf_trace_track_foreign_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_track_foreign_dirty(void *__data, struct folio *folio, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (0)
Location: include/trace/events/writeback.h:237
Inline: False
```
**Symbols:**

```
ffffffff814f51e0-ffffffff814f51f5: __bpf_trace_track_foreign_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_track_foreign_dirty(void *__data, struct folio *folio, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (0)
Location: include/trace/events/writeback.h:237
Inline: False
```
**Symbols:**

```
ffffffff815298f0-ffffffff81529905: __bpf_trace_track_foreign_dirty (STB_LOCAL)
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
void __bpf_trace_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103c3080)
Location: include/trace/events/writeback.h:238
Inline: False
```
**Symbols:**

```
ffff8000103c3080-ffff8000103c3094: __bpf_trace_track_foreign_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a0a04)
Location: include/trace/events/writeback.h:238
Inline: False
```
**Symbols:**

```
c05a0a04-c05a0a2c: __bpf_trace_track_foreign_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004c42e0)
Location: include/trace/events/writeback.h:238
Inline: False
```
**Symbols:**

```
c0000000004c42e0-c0000000004c430c: __bpf_trace_track_foreign_dirty (STB_LOCAL)
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
void __bpf_trace_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81307970)
Location: include/trace/events/writeback.h:238
Inline: False
```
**Symbols:**

```
ffffffff81307970-ffffffff8130797b: __bpf_trace_track_foreign_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812f8590)
Location: include/trace/events/writeback.h:238
Inline: False
```
**Symbols:**

```
ffffffff812f8590-ffffffff812f859b: __bpf_trace_track_foreign_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81305760)
Location: include/trace/events/writeback.h:238
Inline: False
```
**Symbols:**

```
ffffffff81305760-ffffffff8130576b: __bpf_trace_track_foreign_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81316ad0)
Location: include/trace/events/writeback.h:238
Inline: False
```
**Symbols:**

```
ffffffff81316ad0-ffffffff81316adb: __bpf_trace_track_foreign_dirty (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
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
