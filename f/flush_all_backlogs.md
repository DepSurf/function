# Function: <code>flush_all_backlogs</code>

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
In net/core/dev.c (ffffffff817abf41)
Location: net/core/dev.c:4344
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffff817ca4c1)
Location: net/core/dev.c:4558
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffff81843fc1)
Location: net/core/dev.c:4698
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffff81897f00)
Location: net/core/dev.c:4828
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffff818ba242)
Location: net/core/dev.c:5326
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffff818fc6f4)
Location: net/core/dev.c:5336
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffff8192ed22)
Location: net/core/dev.c:5238
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0d749)
Location: net/core/dev.c:5621
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void flush_all_backlogs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5705
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81a046d0-ffffffff81a04864: flush_all_backlogs (STB_LOCAL)
ffffffff81c311b6-ffffffff81c311c2: flush_all_backlogs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void flush_all_backlogs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5829
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
```
**Symbols:**

```
ffffffff819ebee0-ffffffff819ec07d: flush_all_backlogs (STB_LOCAL)
ffffffff81c23499-ffffffff81c234a5: flush_all_backlogs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void flush_all_backlogs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5799
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
```
**Symbols:**

```
ffffffff81a9ce70-ffffffff81a9d07b: flush_all_backlogs (STB_LOCAL)
ffffffff81d3615d-ffffffff81d3617d: flush_all_backlogs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void flush_all_backlogs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5832
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
```
**Symbols:**

```
ffffffff81c0f600-ffffffff81c0f7fc: flush_all_backlogs (STB_LOCAL)
ffffffff81f0263b-ffffffff81f0265b: flush_all_backlogs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void flush_all_backlogs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5823
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
```
**Symbols:**

```
ffffffff81dc1f60-ffffffff81dc2181: flush_all_backlogs (STB_LOCAL)
ffffffff820ab389-ffffffff820ab39d: flush_all_backlogs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void flush_all_backlogs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5799
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
```
**Symbols:**

```
ffffffff81e314c0-ffffffff81e316e1: flush_all_backlogs (STB_LOCAL)
ffffffff8212c9d3-ffffffff8212c9e7: flush_all_backlogs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void flush_all_backlogs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5881
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
```
**Symbols:**

```
ffffffff81eefc40-ffffffff81eefe61: flush_all_backlogs (STB_LOCAL)
ffffffff8220e727-ffffffff8220e73b: flush_all_backlogs.cold (STB_LOCAL)
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
In net/core/dev.c (ffff800010bcbb64)
Location: net/core/dev.c:5238
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (c0ce9b08)
Location: net/core/dev.c:5238
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (c000000000ca844c)
Location: net/core/dev.c:5238
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffe000759496)
Location: net/core/dev.c:5238
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffff818ced22)
Location: net/core/dev.c:5238
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffff81888e42)
Location: net/core/dev.c:5238
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffff8191fd22)
Location: net/core/dev.c:5238
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffff81941a82)
Location: net/core/dev.c:5238
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
