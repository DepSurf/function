# Function: <code>devlink_trap_policer_register</code>

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
int devlink_trap_policer_register(struct devlink *devlink, const struct devlink_trap_policer *policer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5fad0)
Location: net/core/devlink.c:9119
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_policers_register
```
**Symbols:**

```
ffffffff81a5fad0-ffffffff81a5fbe3: devlink_trap_policer_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_trap_policer_register(struct devlink *devlink, const struct devlink_trap_policer *policer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a682c0)
Location: net/core/devlink.c:10073
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_policers_register
```
**Symbols:**

```
ffffffff81a682c0-ffffffff81a683d3: devlink_trap_policer_register (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a43573)
Location: net/core/devlink.c:10337
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policers_register
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
In net/core/devlink.c (ffffffff81af9a53)
Location: net/core/devlink.c:11279
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policers_register
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
In net/core/devlink.c (ffffffff81c7c7db)
Location: net/core/devlink.c:11877
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policers_register
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
In net/core/devlink.c (ffffffff81e410d4)
Location: net/core/devlink.c:12770
Inline: True
Inline callers:
  - net/core/devlink.c:devl_trap_policers_register
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
In net/devlink/leftover.c (ffffffff82037d89)
Location: net/devlink/leftover.c:9365
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_trap_policers_register
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
In net/devlink/trap.c (ffffffff821150d0)
Location: net/devlink/trap.c:1751
Inline: True
Inline callers:
  - net/devlink/trap.c:devl_trap_policers_register
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
