# Function: <code>sysrq_handle_lockdown_lift</code>

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
void sysrq_handle_lockdown_lift(int key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/lock_down.c (ffffffff814250c0)
Location: security/lock_down.c:84
Inline: True
```
**Symbols:**

```
ffffffff814250c0-ffffffff814250e9: sysrq_handle_lockdown_lift (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void sysrq_handle_lockdown_lift(int key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lock_down.c (0)
Location: security/lock_down.c:93
Inline: False
```
**Symbols:**

```
ffffffff81457eb0-ffffffff81457ec8: sysrq_handle_lockdown_lift (STB_LOCAL)
ffffffff81457ef3-ffffffff81457f0b: sysrq_handle_lockdown_lift.cold.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void sysrq_handle_lockdown_lift(int key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lock_down.c (0)
Location: security/lock_down.c:93
Inline: False
```
**Symbols:**

```
ffffffff814753a0-ffffffff814753b8: sysrq_handle_lockdown_lift (STB_LOCAL)
ffffffff814753e3-ffffffff814753fb: sysrq_handle_lockdown_lift.cold.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sysrq_handle_lockdown_lift(int key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lock_down.c (0)
Location: security/lock_down.c:95
Inline: False
```
**Symbols:**

```
ffffffff814a30b0-ffffffff814a30c8: sysrq_handle_lockdown_lift (STB_LOCAL)
ffffffff814a30f3-ffffffff814a310b: sysrq_handle_lockdown_lift.cold (STB_LOCAL)
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
