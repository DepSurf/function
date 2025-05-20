# Function: <code>__do_sys_mq_unlink</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813e0bf5)
Location: ipc/mqueue.c:803
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
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
In ipc/mqueue.c (ffffffff813fb3e5)
Location: ipc/mqueue.c:803
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
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
In ipc/mqueue.c (ffffffff81427755)
Location: ipc/mqueue.c:858
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
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
In ipc/mqueue.c (ffffffff81441485)
Location: ipc/mqueue.c:857
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_mq_unlink(const char *u_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81492330)
Location: ipc/mqueue.c:938
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
**Symbols:**

```
ffffffff81492330-ffffffff8149249d: __do_sys_mq_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_mq_unlink(const char *u_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814afb80)
Location: ipc/mqueue.c:938
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
**Symbols:**

```
ffffffff814afb80-ffffffff814afced: __do_sys_mq_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_mq_unlink(const char *u_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814b59c0)
Location: ipc/mqueue.c:938
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
**Symbols:**

```
ffffffff814b59c0-ffffffff814b5b33: __do_sys_mq_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_mq_unlink(const char *u_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8150e0b0)
Location: ipc/mqueue.c:940
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
**Symbols:**

```
ffffffff8150e0b0-ffffffff8150e223: __do_sys_mq_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_mq_unlink(const char *u_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff815a0ee0)
Location: ipc/mqueue.c:952
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
**Symbols:**

```
ffffffff815a0ee0-ffffffff815a1085: __do_sys_mq_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_mq_unlink(const char *u_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8164a8d0)
Location: ipc/mqueue.c:952
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
**Symbols:**

```
ffffffff8164a8d0-ffffffff8164aa3d: __do_sys_mq_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_mq_unlink(const char *u_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81682c10)
Location: ipc/mqueue.c:952
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
**Symbols:**

```
ffffffff81682c10-ffffffff81682d7d: __do_sys_mq_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_mq_unlink(const char *u_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff816bf010)
Location: ipc/mqueue.c:953
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
**Symbols:**

```
ffffffff816bf010-ffffffff816bf17d: __do_sys_mq_unlink (STB_LOCAL)
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
In ipc/mqueue.c (ffff800010529714)
Location: ipc/mqueue.c:857
Inline: True
Inline callers:
  - ipc/mqueue.c:__arm64_sys_mq_unlink
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
In ipc/mqueue.c (c06e4a50)
Location: ipc/mqueue.c:857
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_unlink
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
In ipc/mqueue.c (c000000000676358)
Location: ipc/mqueue.c:857
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_unlink
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
In ipc/mqueue.c (ffffffe00038db62)
Location: ipc/mqueue.c:857
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_unlink
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
In ipc/mqueue.c (ffffffff81439a65)
Location: ipc/mqueue.c:857
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
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
In ipc/mqueue.c (ffffffff8142a4d5)
Location: ipc/mqueue.c:857
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
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
In ipc/mqueue.c (ffffffff81435c05)
Location: ipc/mqueue.c:857
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
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
In ipc/mqueue.c (ffffffff8144dda5)
Location: ipc/mqueue.c:857
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
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
