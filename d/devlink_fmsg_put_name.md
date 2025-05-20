# Function: <code>devlink_fmsg_put_name</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194f823)
Location: net/core/devlink.c:4130
Inline: True
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
In net/core/devlink.c (ffffffff81987a03)
Location: net/core/devlink.c:4184
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_fmsg_put_name(struct devlink_fmsg *fmsg, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a529a0)
Location: net/core/devlink.c:4631
Inline: False
```
**Symbols:**

```
ffffffff81a529a0-ffffffff81a52a43: devlink_fmsg_put_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_fmsg_put_name(struct devlink_fmsg *fmsg, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a58ee0)
Location: net/core/devlink.c:5320
Inline: False
```
**Symbols:**

```
ffffffff81a58ee0-ffffffff81a58f83: devlink_fmsg_put_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_fmsg_put_name(struct devlink_fmsg *fmsg, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3e4c0)
Location: net/core/devlink.c:5523
Inline: False
```
**Symbols:**

```
ffffffff81a3e4c0-ffffffff81a3e563: devlink_fmsg_put_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_put_name(struct devlink_fmsg *fmsg, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6136
Inline: False
```
**Symbols:**

```
ffffffff81af4a00-ffffffff81af4aac: devlink_fmsg_put_name (STB_LOCAL)
ffffffff81d38604-ffffffff81d38618: devlink_fmsg_put_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_put_name(struct devlink_fmsg *fmsg, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6631
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_fmsg_pair_nest_start
```
**Symbols:**

```
ffffffff81c78cd0-ffffffff81c78d86: devlink_fmsg_put_name (STB_LOCAL)
ffffffff81f04fb5-ffffffff81f04fc9: devlink_fmsg_put_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_put_name(struct devlink_fmsg *fmsg, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7186
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_fmsg_pair_nest_start
```
**Symbols:**

```
ffffffff81e31ba0-ffffffff81e31c56: devlink_fmsg_put_name (STB_LOCAL)
ffffffff820acfb3-ffffffff820acfc7: devlink_fmsg_put_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_put_name(struct devlink_fmsg *fmsg, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:703
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_fmsg_pair_nest_start
```
**Symbols:**

```
ffffffff82045c10-ffffffff82045d31: devlink_fmsg_put_name (STB_LOCAL)
ffffffff821366ad-ffffffff821366e4: devlink_fmsg_put_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void devlink_fmsg_put_name(struct devlink_fmsg *fmsg, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:721
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_fmsg_pair_nest_start
```
**Symbols:**

```
ffffffff821118a0-ffffffff821119be: devlink_fmsg_put_name (STB_LOCAL)
ffffffff822182c7-ffffffff822182ee: devlink_fmsg_put_name.cold (STB_LOCAL)
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
In net/core/devlink.c (ffff800010c25628)
Location: net/core/devlink.c:4184
Inline: True
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
In net/core/devlink.c (c0d44178)
Location: net/core/devlink.c:4184
Inline: True
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
In net/core/devlink.c (c000000000d25a70)
Location: net/core/devlink.c:4184
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_pair_nest_start
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
In net/core/devlink.c (ffffffe00079db32)
Location: net/core/devlink.c:4184
Inline: True
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
In net/core/devlink.c (ffffffff81927873)
Location: net/core/devlink.c:4184
Inline: True
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
In net/core/devlink.c (ffffffff818e1623)
Location: net/core/devlink.c:4184
Inline: True
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
In net/core/devlink.c (ffffffff81978a03)
Location: net/core/devlink.c:4184
Inline: True
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
In net/core/devlink.c (ffffffff8199aef3)
Location: net/core/devlink.c:4184
Inline: True
```
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>
