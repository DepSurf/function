# Function: <code>trace_boot_enable_tracer</code>

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
In kernel/trace/trace_boot.c (ffffffff82cf7846)
Location: kernel/trace/trace_boot.c:266
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void trace_boot_enable_tracer(struct trace_array *tr, struct xbc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_boot.c (ffffffff82fe436d)
Location: kernel/trace/trace_boot.c:276
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
**Symbols:**

```
ffffffff82fe436d-ffffffff82fe43f4: trace_boot_enable_tracer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_boot.c (ffffffff831eeac9)
Location: kernel/trace/trace_boot.c:276
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_boot.c (ffffffff832d409b)
Location: kernel/trace/trace_boot.c:592
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_boot.c (ffffffff8348863b)
Location: kernel/trace/trace_boot.c:592
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_boot.c (ffffffff83eb855f)
Location: kernel/trace/trace_boot.c:592
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_boot.c (ffffffff836dda4f)
Location: kernel/trace/trace_boot.c:592
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_boot.c (ffffffff8391007f)
Location: kernel/trace/trace_boot.c:592
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
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
</ul>
