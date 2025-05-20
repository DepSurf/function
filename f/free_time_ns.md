# Function: <code>free_time_ns</code>

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
void free_time_ns(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8115a000)
Location: kernel/time/namespace.c:229
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_put
```
**Symbols:**

```
ffffffff8115a000-ffffffff8115a05a: free_time_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_time_ns(struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81155f50)
Location: kernel/time/namespace.c:229
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_put
```
**Symbols:**

```
ffffffff81155f50-ffffffff81155fcc: free_time_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_time_ns(struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81157350)
Location: kernel/time/namespace.c:229
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_put
```
**Symbols:**

```
ffffffff81157350-ffffffff811573cc: free_time_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_time_ns(struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8117c1a0)
Location: kernel/time/namespace.c:229
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_put
```
**Symbols:**

```
ffffffff8117c1a0-ffffffff8117c21c: free_time_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_time_ns(struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff811b1910)
Location: kernel/time/namespace.c:229
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_put
```
**Symbols:**

```
ffffffff811b1910-ffffffff811b1993: free_time_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_time_ns(struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff811f26e0)
Location: kernel/time/namespace.c:247
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_put
```
**Symbols:**

```
ffffffff811f26e0-ffffffff811f2763: free_time_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_time_ns(struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81206e60)
Location: kernel/time/namespace.c:247
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_put
```
**Symbols:**

```
ffffffff81206e60-ffffffff81206ee3: free_time_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_time_ns(struct time_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8121e070)
Location: kernel/time/namespace.c:247
Inline: False
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_put
```
**Symbols:**

```
ffffffff8121e070-ffffffff8121e0f3: free_time_ns (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct time_namespace *ns</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kref *kref</code>
</li>
</ul>
</details>
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
