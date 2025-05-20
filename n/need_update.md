# Function: <code>need_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811ad11f)
Location: mm/vmstat.c:1424
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_shepherd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c5970)
Location: mm/vmstat.c:1712
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff811c5970-ffffffff811c59d5: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d5aa0)
Location: mm/vmstat.c:1636
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff811d5aa0-ffffffff811d5b05: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811de7d0)
Location: mm/vmstat.c:1640
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff811de7d0-ffffffff811de835: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f4380)
Location: mm/vmstat.c:1857
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff811f4380-ffffffff811f4405: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812156b0)
Location: mm/vmstat.c:1814
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff812156b0-ffffffff81215735: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812285a0)
Location: mm/vmstat.c:1816
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff812285a0-ffffffff81228628: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812382c0)
Location: mm/vmstat.c:1812
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff812382c0-ffffffff81238348: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81246550)
Location: mm/vmstat.c:1831
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff81246550-ffffffff812465d8: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81274150)
Location: mm/vmstat.c:1840
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff81274150-ffffffff812741d8: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127e9a0)
Location: mm/vmstat.c:1883
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff8127e9a0-ffffffff8127ea28: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81283b00)
Location: mm/vmstat.c:1924
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff81283b00-ffffffff81283bca: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c1f40)
Location: mm/vmstat.c:1926
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff812c1f40-ffffffff812c2032: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8131f0e0)
Location: mm/vmstat.c:1955
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff8131f0e0-ffffffff8131f1d1: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81392c10)
Location: mm/vmstat.c:1950
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff81392c10-ffffffff81392d01: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c5650)
Location: mm/vmstat.c:1960
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff813c5650-ffffffff813c5741: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f0050)
Location: mm/vmstat.c:1964
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff813f0050-ffffffff813f0141: need_update (STB_LOCAL)
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
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102d98e0)
Location: mm/vmstat.c:1831
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffff8000102d98e0-ffff8000102d9984: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c05008d0)
Location: mm/vmstat.c:1831
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
c05008d0-c050094c: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c000000000399c40)
Location: mm/vmstat.c:1831
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
c000000000399c40-c000000000399d30: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f3cb2)
Location: mm/vmstat.c:1831
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffe0001f3cb2-ffffffe0001f3d2c: need_update (STB_LOCAL)
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
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123eba0)
Location: mm/vmstat.c:1831
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff8123eba0-ffffffff8123ec28: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81231ba0)
Location: mm/vmstat.c:1831
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff81231ba0-ffffffff81231c28: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123c940)
Location: mm/vmstat.c:1831
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff8123c940-ffffffff8123c9c8: need_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool need_update(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124c080)
Location: mm/vmstat.c:1831
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:quiet_vmstat
```
**Symbols:**

```
ffffffff8124c080-ffffffff8124c108: need_update (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
