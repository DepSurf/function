# Function: <code>rproc_trigger_recovery</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rproc_trigger_recovery(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f5cf7)
Location: drivers/remoteproc/remoteproc_core.c:1651
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
```
**Symbols:**

```
ffffffff818f5cf7-ffffffff818f5f8a: rproc_trigger_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int rproc_trigger_recovery(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:1708
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
```
**Symbols:**

```
ffffffff819cc02b-ffffffff819cc0ac: rproc_trigger_recovery.cold (STB_LOCAL)
ffffffff819caed0-ffffffff819caf48: rproc_trigger_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int rproc_trigger_recovery(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:1686
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
```
**Symbols:**

```
ffffffff81c2ebed-ffffffff81c2ec76: rproc_trigger_recovery.cold (STB_LOCAL)
ffffffff819ca890-ffffffff819ca908: rproc_trigger_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rproc_trigger_recovery(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:1884
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
```
**Symbols:**

```
ffffffff81c20ec7-ffffffff81c20f53: rproc_trigger_recovery.cold (STB_LOCAL)
ffffffff819afa20-ffffffff819afa98: rproc_trigger_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rproc_trigger_recovery(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:1902
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
```
**Symbols:**

```
ffffffff81d3284f-ffffffff81d328db: rproc_trigger_recovery.cold (STB_LOCAL)
ffffffff81a5e080-ffffffff81a5e0f8: rproc_trigger_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rproc_trigger_recovery(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:1898
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
```
**Symbols:**

```
ffffffff81efed32-ffffffff81efedbb: rproc_trigger_recovery.cold (STB_LOCAL)
ffffffff81bce290-ffffffff81bce316: rproc_trigger_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rproc_trigger_recovery(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d79020)
Location: drivers/remoteproc/remoteproc_core.c:1830
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
```
**Symbols:**

```
ffffffff81d79020-ffffffff81d79157: rproc_trigger_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rproc_trigger_recovery(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de6f70)
Location: drivers/remoteproc/remoteproc_core.c:1831
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
```
**Symbols:**

```
ffffffff81de6f70-ffffffff81de70a7: rproc_trigger_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rproc_trigger_recovery(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9d150)
Location: drivers/remoteproc/remoteproc_core.c:1831
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
  - drivers/remoteproc/remoteproc_sysfs.c:recovery_store
```
**Symbols:**

```
ffffffff81e9d150-ffffffff81e9d287: rproc_trigger_recovery (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int rproc_trigger_recovery(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffff800010b81c78)
Location: drivers/remoteproc/remoteproc_core.c:1651
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
```
**Symbols:**

```
ffff800010b81c78-ffff800010b81f10: rproc_trigger_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rproc_trigger_recovery(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c0c65178)
Location: drivers/remoteproc/remoteproc_core.c:1651
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
```
**Symbols:**

```
c0c65178-c0c65434: rproc_trigger_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rproc_trigger_recovery(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c000000000c5e9dc)
Location: drivers/remoteproc/remoteproc_core.c:1651
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
```
**Symbols:**

```
c000000000c5e9dc-c000000000c5ed18: rproc_trigger_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int rproc_trigger_recovery(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81897027)
Location: drivers/remoteproc/remoteproc_core.c:1651
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
```
**Symbols:**

```
ffffffff81897027-ffffffff818972ba: rproc_trigger_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rproc_trigger_recovery(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81907787)
Location: drivers/remoteproc/remoteproc_core.c:1651
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_crash_handler_work
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
```
**Symbols:**

```
ffffffff81907787-ffffffff81907a1a: rproc_trigger_recovery (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
