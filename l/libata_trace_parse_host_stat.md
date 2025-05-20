# Function: <code>libata_trace_parse_host_stat</code>

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
const char *libata_trace_parse_host_stat(struct trace_seq *p, unsigned char host_stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-trace.c (ffffffff81a38120)
Location: drivers/ata/libata-trace.c:42
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:trace_raw_output_ata_bmdma_status
```
**Symbols:**

```
ffffffff81a38120-ffffffff81a381d3: libata_trace_parse_host_stat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *libata_trace_parse_host_stat(struct trace_seq *p, unsigned char host_stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-trace.c (ffffffff81bbd070)
Location: drivers/ata/libata-trace.c:42
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:trace_raw_output_ata_bmdma_status
```
**Symbols:**

```
ffffffff81bbd070-ffffffff81bbd123: libata_trace_parse_host_stat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *libata_trace_parse_host_stat(struct trace_seq *p, unsigned char host_stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-trace.c (ffffffff81c148e0)
Location: drivers/ata/libata-trace.c:42
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:trace_raw_output_ata_bmdma_status
```
**Symbols:**

```
ffffffff81c148e0-ffffffff81c14993: libata_trace_parse_host_stat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *libata_trace_parse_host_stat(struct trace_seq *p, unsigned char host_stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-trace.c (ffffffff81c69ae0)
Location: drivers/ata/libata-trace.c:42
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:trace_raw_output_ata_bmdma_status
```
**Symbols:**

```
ffffffff81c69ae0-ffffffff81c69b93: libata_trace_parse_host_stat (STB_GLOBAL)
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
