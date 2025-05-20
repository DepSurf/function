# Function: <code>apparmor_task_getsecid_obj</code>

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
void apparmor_task_getsecid_obj(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff816214c0)
Location: security/apparmor/lsm.c:971
Inline: False
```
**Symbols:**

```
ffffffff816214c0-ffffffff81621522: apparmor_task_getsecid_obj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void apparmor_task_getsecid_obj(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff816d4d00)
Location: security/apparmor/lsm.c:1021
Inline: False
```
**Symbols:**

```
ffffffff816d4d00-ffffffff816d4d62: apparmor_task_getsecid_obj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void apparmor_task_getsecid_obj(struct task_struct *p, u32 *secid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8170de80)
Location: security/apparmor/lsm.c:1169
Inline: False
```
**Symbols:**

```
ffffffff8170de80-ffffffff8170dee2: apparmor_task_getsecid_obj (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
