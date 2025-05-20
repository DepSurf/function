# Function: <code>__register_sysctl_base</code>

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
int __register_sysctl_base(struct ctl_table *base_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814adc50)
Location: fs/proc/proc_sysctl.c:1660
Inline: False
Direct callers:
  - kernel/sysctl.c:sysctl_init_bases
  - kernel/sysctl.c:sysctl_init_bases
  - kernel/sysctl.c:sysctl_init_bases
  - kernel/sysctl.c:sysctl_init_bases
```
**Symbols:**

```
ffffffff814adc50-ffffffff814adc7d: __register_sysctl_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __register_sysctl_base(struct ctl_table *base_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81544180)
Location: fs/proc/proc_sysctl.c:1659
Inline: False
Direct callers:
  - kernel/sysctl.c:sysctl_init_bases
  - kernel/sysctl.c:sysctl_init_bases
  - kernel/sysctl.c:sysctl_init_bases
  - kernel/sysctl.c:sysctl_init_bases
```
**Symbols:**

```
ffffffff81544180-ffffffff815441ad: __register_sysctl_base (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
