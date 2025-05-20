# Function: <code>trace_boot_init_instances</code>

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
void trace_boot_init_instances(struct xbc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_boot.c (ffffffff82cf78e1)
Location: kernel/trace/trace_boot.c:289
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff82cf78e1-ffffffff82cf796a: trace_boot_init_instances (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void trace_boot_init_instances(struct xbc_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_boot.c (ffffffff82fe4487)
Location: kernel/trace/trace_boot.c:305
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff82fe4487-ffffffff82fe4510: trace_boot_init_instances (STB_LOCAL)
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
In kernel/trace/trace_boot.c (ffffffff831eebec)
Location: kernel/trace/trace_boot.c:305
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
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
In kernel/trace/trace_boot.c (ffffffff832d4176)
Location: kernel/trace/trace_boot.c:621
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
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
In kernel/trace/trace_boot.c (ffffffff83488723)
Location: kernel/trace/trace_boot.c:621
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
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
In kernel/trace/trace_boot.c (ffffffff83eb86c7)
Location: kernel/trace/trace_boot.c:621
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
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
In kernel/trace/trace_boot.c (ffffffff836ddbb7)
Location: kernel/trace/trace_boot.c:621
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
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
In kernel/trace/trace_boot.c (ffffffff839101e7)
Location: kernel/trace/trace_boot.c:621
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
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
</ul>
