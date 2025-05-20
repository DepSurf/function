# Function: <code>__do_sys_process_mrelease</code>

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
long int __do_sys_process_mrelease(int pidfd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812a3150)
Location: mm/oom_kill.c:1143
Inline: False
Direct callers:
  - mm/oom_kill.c:__ia32_sys_process_mrelease
  - mm/oom_kill.c:__x64_sys_process_mrelease
```
**Symbols:**

```
ffffffff812a3150-ffffffff812a3344: __do_sys_process_mrelease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_process_mrelease(int pidfd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812fb010)
Location: mm/oom_kill.c:1201
Inline: False
Direct callers:
  - mm/oom_kill.c:__ia32_sys_process_mrelease
  - mm/oom_kill.c:__x64_sys_process_mrelease
```
**Symbols:**

```
ffffffff812fb010-ffffffff812fb254: __do_sys_process_mrelease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_process_mrelease(int pidfd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81364360)
Location: mm/oom_kill.c:1200
Inline: False
Direct callers:
  - mm/oom_kill.c:__ia32_sys_process_mrelease
  - mm/oom_kill.c:__x64_sys_process_mrelease
```
**Symbols:**

```
ffffffff81364360-ffffffff813645bc: __do_sys_process_mrelease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_process_mrelease(int pidfd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81396830)
Location: mm/oom_kill.c:1198
Inline: False
Direct callers:
  - mm/oom_kill.c:__ia32_sys_process_mrelease
  - mm/oom_kill.c:__x64_sys_process_mrelease
```
**Symbols:**

```
ffffffff81396830-ffffffff81396a8d: __do_sys_process_mrelease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_process_mrelease(int pidfd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813c0140)
Location: mm/oom_kill.c:1196
Inline: False
Direct callers:
  - mm/oom_kill.c:__ia32_sys_process_mrelease
  - mm/oom_kill.c:__x64_sys_process_mrelease
```
**Symbols:**

```
ffffffff813c0140-ffffffff813c039d: __do_sys_process_mrelease (STB_LOCAL)
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
