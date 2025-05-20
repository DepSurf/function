# Function: <code>negotiate_mq</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int negotiate_mq(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815cdf60)
Location: drivers/block/xen-blkfront.c:1879
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff815cdf60-ffffffff815ce0fb: negotiate_mq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int negotiate_mq(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815fab70)
Location: drivers/block/xen-blkfront.c:1874
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff815fab70-ffffffff815facb5: negotiate_mq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int negotiate_mq(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8160e950)
Location: drivers/block/xen-blkfront.c:1887
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff8160e950-ffffffff8160ea91: negotiate_mq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int negotiate_mq(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816771d0)
Location: drivers/block/xen-blkfront.c:1887
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff816771d0-ffffffff81677311: negotiate_mq (STB_LOCAL)
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
In drivers/block/xen-blkfront.c (ffffffff816ae939)
Location: drivers/block/xen-blkfront.c:1894
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
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
In drivers/block/xen-blkfront.c (ffffffff816d3109)
Location: drivers/block/xen-blkfront.c:1902
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
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
In drivers/block/xen-blkfront.c (ffffffff8170e79d)
Location: drivers/block/xen-blkfront.c:1902
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
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
In drivers/block/xen-blkfront.c (ffffffff81732a9d)
Location: drivers/block/xen-blkfront.c:1902
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int negotiate_mq(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817eba30)
Location: drivers/block/xen-blkfront.c:1910
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff817eba30-ffffffff817ebf31: negotiate_mq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int negotiate_mq(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81800360)
Location: drivers/block/xen-blkfront.c:1911
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff81800360-ffffffff81800861: negotiate_mq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int negotiate_mq(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817e5080)
Location: drivers/block/xen-blkfront.c:1911
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff817e5080-ffffffff817e558e: negotiate_mq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int negotiate_mq(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81871790)
Location: drivers/block/xen-blkfront.c:1900
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff81871790-ffffffff81871c7d: negotiate_mq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int negotiate_mq(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff819b9810)
Location: drivers/block/xen-blkfront.c:1884
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff819b9810-ffffffff819b9cc3: negotiate_mq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int negotiate_mq(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b2ec50)
Location: drivers/block/xen-blkfront.c:1894
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff81b2ec50-ffffffff81b2f103: negotiate_mq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int negotiate_mq(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b820c0)
Location: drivers/block/xen-blkfront.c:1895
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff81b820c0-ffffffff81b82567: negotiate_mq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int negotiate_mq(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81bd5f80)
Location: drivers/block/xen-blkfront.c:1895
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff81bd5f80-ffffffff81bd6427: negotiate_mq (STB_LOCAL)
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
In drivers/block/xen-blkfront.c (ffff80001092768c)
Location: drivers/block/xen-blkfront.c:1902
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816f8a4d)
Location: drivers/block/xen-blkfront.c:1927
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81725f5d)
Location: drivers/block/xen-blkfront.c:1902
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
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
In drivers/block/xen-blkfront.c (ffffffff817413ad)
Location: drivers/block/xen-blkfront.c:1902
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
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
