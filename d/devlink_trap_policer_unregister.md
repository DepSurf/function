# Function: <code>devlink_trap_policer_unregister</code>

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
void devlink_trap_policer_unregister(struct devlink *devlink, const struct devlink_trap_policer *policer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5fbf0)
Location: net/core/devlink.c:9154
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_policers_unregister
  - net/core/devlink.c:devlink_trap_policers_register
```
**Symbols:**

```
ffffffff81a5fbf0-ffffffff81a5fcb0: devlink_trap_policer_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devlink_trap_policer_unregister(struct devlink *devlink, const struct devlink_trap_policer *policer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a683e0)
Location: net/core/devlink.c:10108
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_policers_unregister
  - net/core/devlink.c:devlink_trap_policers_register
```
**Symbols:**

```
ffffffff81a683e0-ffffffff81a684a0: devlink_trap_policer_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devlink_trap_policer_unregister(struct devlink *devlink, const struct devlink_trap_policer *policer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a433c0)
Location: net/core/devlink.c:10372
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_policers_unregister
  - net/core/devlink.c:devlink_trap_policers_register
```
**Symbols:**

```
ffffffff81a433c0-ffffffff81a43480: devlink_trap_policer_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_trap_policer_unregister(struct devlink *devlink, const struct devlink_trap_policer *policer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af98a0)
Location: net/core/devlink.c:11314
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_policers_unregister
  - net/core/devlink.c:devlink_trap_policers_register
```
**Symbols:**

```
ffffffff81af98a0-ffffffff81af9960: devlink_trap_policer_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_trap_policer_unregister(struct devlink *devlink, const struct devlink_trap_policer *policer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7c670)
Location: net/core/devlink.c:11912
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_policers_unregister
  - net/core/devlink.c:devlink_trap_policers_register
```
**Symbols:**

```
ffffffff81c7c670-ffffffff81c7c744: devlink_trap_policer_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devlink_trap_policer_unregister(struct devlink *devlink, const struct devlink_trap_policer *policer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e40f70)
Location: net/core/devlink.c:12805
Inline: False
Direct callers:
  - net/core/devlink.c:devl_trap_policers_unregister
  - net/core/devlink.c:devl_trap_policers_register
```
**Symbols:**

```
ffffffff81e40f70-ffffffff81e41044: devlink_trap_policer_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devlink_trap_policer_unregister(struct devlink *devlink, const struct devlink_trap_policer *policer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82037c20)
Location: net/devlink/leftover.c:9400
Inline: False
Direct callers:
  - net/devlink/leftover.c:devl_trap_policers_unregister
  - net/devlink/leftover.c:devl_trap_policers_register
```
**Symbols:**

```
ffffffff82037c20-ffffffff82037cf4: devlink_trap_policer_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devlink_trap_policer_unregister(struct devlink *devlink, const struct devlink_trap_policer *policer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/trap.c (ffffffff82114f70)
Location: net/devlink/trap.c:1786
Inline: False
Direct callers:
  - net/devlink/trap.c:devl_trap_policers_unregister
  - net/devlink/trap.c:devl_trap_policers_register
```
**Symbols:**

```
ffffffff82114f70-ffffffff82115044: devlink_trap_policer_unregister (STB_LOCAL)
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
