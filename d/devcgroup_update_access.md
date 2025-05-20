# Function: <code>devcgroup_update_access</code>

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
In security/device_cgroup.c (ffffffff81395b0c)
Location: security/device_cgroup.c:604
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff813d185c)
Location: security/device_cgroup.c:604
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff813e8f8c)
Location: security/device_cgroup.c:604
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff813f5399)
Location: security/device_cgroup.c:604
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff8141d659)
Location: security/device_cgroup.c:596
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff8144f921)
Location: security/device_cgroup.c:596
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff8146c901)
Location: security/device_cgroup.c:596
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff8149a009)
Location: security/device_cgroup.c:595
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff814b4209)
Location: security/device_cgroup.c:595
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devcgroup_update_access(struct dev_cgroup *devcgroup, int filetype, char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff815136c0)
Location: security/device_cgroup.c:598
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_access_write
```
**Symbols:**

```
ffffffff815136c0-ffffffff81513a7a: devcgroup_update_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devcgroup_update_access(struct dev_cgroup *devcgroup, int filetype, char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81530810)
Location: security/device_cgroup.c:598
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_access_write
```
**Symbols:**

```
ffffffff81530810-ffffffff81530bca: devcgroup_update_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devcgroup_update_access(struct dev_cgroup *devcgroup, int filetype, char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81536a10)
Location: security/device_cgroup.c:598
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_access_write
```
**Symbols:**

```
ffffffff81536a10-ffffffff81536dc6: devcgroup_update_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devcgroup_update_access(struct dev_cgroup *devcgroup, int filetype, char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81595140)
Location: security/device_cgroup.c:598
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_access_write
```
**Symbols:**

```
ffffffff81595140-ffffffff81595540: devcgroup_update_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devcgroup_update_access(struct dev_cgroup *devcgroup, int filetype, char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81637330)
Location: security/device_cgroup.c:599
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_access_write
```
**Symbols:**

```
ffffffff81637330-ffffffff81637778: devcgroup_update_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devcgroup_update_access(struct dev_cgroup *devcgroup, int filetype, char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff816ee5b0)
Location: security/device_cgroup.c:610
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_access_write
```
**Symbols:**

```
ffffffff816ee5b0-ffffffff816eeb00: devcgroup_update_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devcgroup_update_access(struct dev_cgroup *devcgroup, int filetype, char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81728aa0)
Location: security/device_cgroup.c:610
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_access_write
```
**Symbols:**

```
ffffffff81728aa0-ffffffff81728ff3: devcgroup_update_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devcgroup_update_access(struct dev_cgroup *devcgroup, int filetype, char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81769e00)
Location: security/device_cgroup.c:610
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_access_write
```
**Symbols:**

```
ffffffff81769e00-ffffffff8176a353: devcgroup_update_access (STB_LOCAL)
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
In security/device_cgroup.c (ffff8000105ac184)
Location: security/device_cgroup.c:595
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (c075bc04)
Location: security/device_cgroup.c:595
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (c00000000072a4ac)
Location: security/device_cgroup.c:595
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffe0003f4916)
Location: security/device_cgroup.c:595
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff814ac7e9)
Location: security/device_cgroup.c:595
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff8149d209)
Location: security/device_cgroup.c:595
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff814a8889)
Location: security/device_cgroup.c:595
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff814c1241)
Location: security/device_cgroup.c:595
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
