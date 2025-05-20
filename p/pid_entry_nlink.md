# Function: <code>pid_entry_nlink</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81ff7fc7)
Location: fs/proc/base.c:145
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff820db025)
Location: fs/proc/base.c:154
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff826e3ce4)
Location: fs/proc/base.c:155
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8270e292)
Location: fs/proc/base.c:151
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff828c54b8)
Location: fs/proc/base.c:155
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff828dea0d)
Location: fs/proc/base.c:155
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff828e73e5)
Location: fs/proc/base.c:155
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int pid_entry_nlink(const struct pid_entry *entries, unsigned int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff82d01b25)
Location: fs/proc/base.c:157
Inline: False
Direct callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
**Symbols:**

```
ffffffff82d01b25-ffffffff82d01b59: pid_entry_nlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int pid_entry_nlink(const struct pid_entry *entries, unsigned int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff82feee14)
Location: fs/proc/base.c:157
Inline: False
Direct callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
**Symbols:**

```
ffffffff82feee14-ffffffff82feee48: pid_entry_nlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int pid_entry_nlink(const struct pid_entry *entries, unsigned int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff831f96d3)
Location: fs/proc/base.c:156
Inline: False
Direct callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
**Symbols:**

```
ffffffff831f96d3-ffffffff831f9707: pid_entry_nlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int pid_entry_nlink(const struct pid_entry *entries, unsigned int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff832e060b)
Location: fs/proc/base.c:158
Inline: False
Direct callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
**Symbols:**

```
ffffffff832e060b-ffffffff832e063f: pid_entry_nlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int pid_entry_nlink(const struct pid_entry *entries, unsigned int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff83496529)
Location: fs/proc/base.c:157
Inline: False
Direct callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
**Symbols:**

```
ffffffff83496529-ffffffff83496568: pid_entry_nlink (STB_LOCAL)
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
In fs/proc/base.c (ffffffff83ecb4e5)
Location: fs/proc/base.c:158
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
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
In fs/proc/base.c (ffffffff836f0565)
Location: fs/proc/base.c:159
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
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
In fs/proc/base.c (ffffffff839235f5)
Location: fs/proc/base.c:159
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff800011460e0c)
Location: fs/proc/base.c:155
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c1538fd4)
Location: fs/proc/base.c:155
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c00000000138c6d4)
Location: fs/proc/base.c:155
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe00001d7b0)
Location: fs/proc/base.c:155
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff828d0299)
Location: fs/proc/base.c:155
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff828c89b5)
Location: fs/proc/base.c:155
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff828e3019)
Location: fs/proc/base.c:155
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff828e842f)
Location: fs/proc/base.c:155
Inline: True
Inline callers:
  - fs/proc/base.c:set_proc_pid_nlink
  - fs/proc/base.c:set_proc_pid_nlink
```
</details>
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
</ul>
