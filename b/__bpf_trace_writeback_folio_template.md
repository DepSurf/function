# Function: <code>__bpf_trace_writeback_folio_template</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_writeback_folio_template(void *__data, struct folio *folio, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81431600)
Location: include/trace/events/writeback.h:55
Inline: True
```
**Symbols:**

```
ffffffff81431600-ffffffff81431615: __bpf_trace_writeback_folio_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_writeback_folio_template(void *__data, struct folio *folio, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814bf3d0)
Location: include/trace/events/writeback.h:55
Inline: True
```
**Symbols:**

```
ffffffff814bf3d0-ffffffff814bf3e5: __bpf_trace_writeback_folio_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_writeback_folio_template(void *__data, struct folio *folio, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f44d0)
Location: include/trace/events/writeback.h:55
Inline: True
```
**Symbols:**

```
ffffffff814f44d0-ffffffff814f44e5: __bpf_trace_writeback_folio_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_writeback_folio_template(void *__data, struct folio *folio, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81528be0)
Location: include/trace/events/writeback.h:55
Inline: True
```
**Symbols:**

```
ffffffff81528be0-ffffffff81528bf5: __bpf_trace_writeback_folio_template (STB_LOCAL)
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
