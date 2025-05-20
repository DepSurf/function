# Function: <code>devlink_trap_notify</code>

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
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81983e40)
Location: net/core/devlink.c:7769
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
ffffffff81983e40-ffffffff81983f01: devlink_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5eab0)
Location: net/core/devlink.c:8708
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_trap_register
```
**Symbols:**

```
ffffffff81a5eab0-ffffffff81a5eb5e: devlink_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a65910)
Location: net/core/devlink.c:9666
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_trap_register
```
**Symbols:**

```
ffffffff81a65910-ffffffff81a659bd: devlink_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4b2a0)
Location: net/core/devlink.c:9930
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
ffffffff81a4b2a0-ffffffff81a4b34d: devlink_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b03b10)
Location: net/core/devlink.c:10872
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
ffffffff81b03b10-ffffffff81b03bbd: devlink_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c85000)
Location: net/core/devlink.c:11466
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
```
**Symbols:**

```
ffffffff81c85000-ffffffff81c85114: devlink_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e3f180)
Location: net/core/devlink.c:12282
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_notify_unregister
  - net/core/devlink.c:devlink_notify_register
```
**Symbols:**

```
ffffffff81e3f180-ffffffff81e3f294: devlink_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8203f940)
Location: net/devlink/leftover.c:8877
Inline: True
Direct callers:
  - net/devlink/leftover.c:devlink_trap_unregister
  - net/devlink/leftover.c:devlink_notify_unregister
  - net/devlink/leftover.c:devlink_notify_register
```
**Symbols:**

```
ffffffff8203f940-ffffffff8203fa55: devlink_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/trap.c (ffffffff82116340)
Location: net/devlink/trap.c:1228
Inline: True
Direct callers:
  - net/devlink/trap.c:devlink_trap_unregister
  - net/devlink/trap.c:devlink_traps_notify_unregister
  - net/devlink/trap.c:devlink_traps_notify_register
```
**Symbols:**

```
ffffffff82116340-ffffffff821164f6: devlink_trap_notify (STB_LOCAL)
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
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2c488)
Location: net/core/devlink.c:7769
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
ffff800010c2c488-ffff800010c2c548: devlink_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d43004)
Location: net/core/devlink.c:7769
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
c0d43004-c0d430ec: devlink_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d23130)
Location: net/core/devlink.c:7769
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
c000000000d23130-c000000000d23258: devlink_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a39ca)
Location: net/core/devlink.c:7769
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
ffffffe0007a39ca-ffffffe0007a3a66: devlink_trap_notify (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81923cb0)
Location: net/core/devlink.c:7769
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
ffffffff81923cb0-ffffffff81923d71: devlink_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dda60)
Location: net/core/devlink.c:7769
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
ffffffff818dda60-ffffffff818ddb21: devlink_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81974e40)
Location: net/core/devlink.c:7769
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
ffffffff81974e40-ffffffff81974f01: devlink_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devlink_trap_notify(struct devlink *devlink, const struct devlink_trap_item *trap_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81997330)
Location: net/core/devlink.c:7769
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
ffffffff81997330-ffffffff819973f1: devlink_trap_notify (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
