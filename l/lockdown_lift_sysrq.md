# Function: <code>lockdown_lift_sysrq</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int lockdown_lift_sysrq();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/lock_down.c (ffffffff826ee360)
Location: security/lock_down.c:97
Inline: True
```
**Symbols:**

```
ffffffff826ee360-ffffffff826ee395: lockdown_lift_sysrq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int lockdown_lift_sysrq();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lock_down.c (ffffffff8271895a)
Location: security/lock_down.c:106
Inline: False
```
**Symbols:**

```
ffffffff8271895a-ffffffff8271898f: lockdown_lift_sysrq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int lockdown_lift_sysrq();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lock_down.c (ffffffff828d09bf)
Location: security/lock_down.c:106
Inline: False
```
**Symbols:**

```
ffffffff828d09bf-ffffffff828d09f4: lockdown_lift_sysrq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int lockdown_lift_sysrq();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lock_down.c (ffffffff828ea75b)
Location: security/lock_down.c:108
Inline: False
```
**Symbols:**

```
ffffffff828ea75b-ffffffff828ea790: lockdown_lift_sysrq (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
