# Function: <code>security_perf_event_read</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_perf_event_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814acb40)
Location: security/security.c:3007
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff814acb40-ffffffff814acb7a: security_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_perf_event_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ca140)
Location: security/security.c:3025
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff814ca140-ffffffff814ca17a: security_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_perf_event_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814d0770)
Location: security/security.c:3088
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff814d0770-ffffffff814d07aa: security_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_perf_event_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815294a0)
Location: security/security.c:3096
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff815294a0-ffffffff815294da: security_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_perf_event_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815beb40)
Location: security/security.c:3174
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff815beb40-ffffffff815beb8d: security_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_perf_event_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8166ae60)
Location: security/security.c:3154
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff8166ae60-ffffffff8166aead: security_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_perf_event_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a35c0)
Location: security/security.c:5648
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff816a35c0-ffffffff816a360d: security_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_perf_event_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816e0040)
Location: security/security.c:5789
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff816e0040-ffffffff816e008d: security_perf_event_read (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
