# Function: <code>cmd_attr_pid</code>

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
In kernel/taskstats.c (ffffffff8113e932)
Location: kernel/taskstats.c:510
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81146f62)
Location: kernel/taskstats.c:483
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81150e05)
Location: kernel/taskstats.c:482
Inline: True
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
In kernel/taskstats.c (ffffffff81153588)
Location: kernel/taskstats.c:496
Inline: True
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
In kernel/taskstats.c (ffffffff8115fd88)
Location: kernel/taskstats.c:496
Inline: True
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
In kernel/taskstats.c (ffffffff8116ed16)
Location: kernel/taskstats.c:492
Inline: True
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
In kernel/taskstats.c (ffffffff8117c816)
Location: kernel/taskstats.c:492
Inline: True
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
In kernel/taskstats.c (ffffffff811896b9)
Location: kernel/taskstats.c:482
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
In kernel/taskstats.c (ffffffff811955f9)
Location: kernel/taskstats.c:482
Inline: True
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
In kernel/taskstats.c (ffffffff811aaa53)
Location: kernel/taskstats.c:482
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811a8003)
Location: kernel/taskstats.c:478
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cmd_attr_pid(struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811a8780)
Location: kernel/taskstats.c:478
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff811a8780-ffffffff811a88e3: cmd_attr_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cmd_attr_pid(struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811d22e0)
Location: kernel/taskstats.c:478
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff811d22e0-ffffffff811d2443: cmd_attr_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cmd_attr_pid(struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff812069a0)
Location: kernel/taskstats.c:500
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff812069a0-ffffffff81206b20: cmd_attr_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cmd_attr_pid(struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8124ecd0)
Location: kernel/taskstats.c:500
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff8124ecd0-ffffffff8124ee50: cmd_attr_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cmd_attr_pid(struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81266080)
Location: kernel/taskstats.c:500
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff81266080-ffffffff81266200: cmd_attr_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cmd_attr_pid(struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8127ff70)
Location: kernel/taskstats.c:499
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff8127ff70-ffffffff812800f0: cmd_attr_pid (STB_LOCAL)
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
In kernel/taskstats.c (ffff80001020d828)
Location: kernel/taskstats.c:482
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
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
In kernel/taskstats.c (c044c2c8)
Location: kernel/taskstats.c:482
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
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
In kernel/taskstats.c (c00000000028b890)
Location: kernel/taskstats.c:482
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
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
In kernel/taskstats.c (ffffffe00016e84a)
Location: kernel/taskstats.c:482
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
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
In kernel/taskstats.c (ffffffff8118dc19)
Location: kernel/taskstats.c:482
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
In kernel/taskstats.c (ffffffff81180d39)
Location: kernel/taskstats.c:482
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
In kernel/taskstats.c (ffffffff8118b9e9)
Location: kernel/taskstats.c:482
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
In kernel/taskstats.c (ffffffff81199363)
Location: kernel/taskstats.c:482
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
