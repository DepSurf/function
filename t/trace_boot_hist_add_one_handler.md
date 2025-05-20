# Function: <code>trace_boot_hist_add_one_handler</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int trace_boot_hist_add_one_handler(struct xbc_node *hnode, char **bufp, char *end, const char *handler, const char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_boot.c (ffffffff832d3416)
Location: kernel/trace/trace_boot.c:247
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
```
**Symbols:**

```
ffffffff832d3416-ffffffff832d35c0: trace_boot_hist_add_one_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int trace_boot_hist_add_one_handler(struct xbc_node *hnode, char **bufp, char *end, const char *handler, const char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_boot.c (ffffffff8348794c)
Location: kernel/trace/trace_boot.c:247
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
```
**Symbols:**

```
ffffffff8348794c-ffffffff83487afe: trace_boot_hist_add_one_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_boot_hist_add_one_handler(struct xbc_node *hnode, char **bufp, char *end, const char *handler, const char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_boot.c (ffffffff83eb7560)
Location: kernel/trace/trace_boot.c:247
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
```
**Symbols:**

```
ffffffff83eb7560-ffffffff83eb7722: trace_boot_hist_add_one_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_boot_hist_add_one_handler(struct xbc_node *hnode, char **bufp, char *end, const char *handler, const char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_boot.c (ffffffff836dcb20)
Location: kernel/trace/trace_boot.c:247
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
```
**Symbols:**

```
ffffffff836dcb20-ffffffff836dcce2: trace_boot_hist_add_one_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_boot_hist_add_one_handler(struct xbc_node *hnode, char **bufp, char *end, const char *handler, const char *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_boot.c (ffffffff8390f150)
Location: kernel/trace/trace_boot.c:247
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
```
**Symbols:**

```
ffffffff8390f150-ffffffff8390f312: trace_boot_hist_add_one_handler (STB_LOCAL)
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
