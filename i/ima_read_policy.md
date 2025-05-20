# Function: <code>ima_read_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_fs.c (ffffffff813d2a67)
Location: security/integrity/ima/ima_fs.c:261
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
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
In security/integrity/ima/ima_fs.c (ffffffff813ea357)
Location: security/integrity/ima/ima_fs.c:275
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
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
In security/integrity/ima/ima_fs.c (ffffffff813f68e8)
Location: security/integrity/ima/ima_fs.c:275
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
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
In security/integrity/ima/ima_fs.c (ffffffff8141ea08)
Location: security/integrity/ima/ima_fs.c:275
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
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
In security/integrity/ima/ima_fs.c (ffffffff81450a18)
Location: security/integrity/ima/ima_fs.c:278
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
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
In security/integrity/ima/ima_fs.c (ffffffff8146d9f8)
Location: security/integrity/ima/ima_fs.c:279
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
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
In security/integrity/ima/ima_fs.c (ffffffff8149b0e4)
Location: security/integrity/ima/ima_fs.c:275
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
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
In security/integrity/ima/ima_fs.c (ffffffff814b5324)
Location: security/integrity/ima/ima_fs.c:275
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t ima_read_policy(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:273
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
```
**Symbols:**

```
ffffffff81514630-ffffffff8151474f: ima_read_policy (STB_LOCAL)
ffffffff81514db1-ffffffff81514dc8: ima_read_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t ima_read_policy(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:274
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
```
**Symbols:**

```
ffffffff81531710-ffffffff8153182e: ima_read_policy (STB_LOCAL)
ffffffff81bf1aec-ffffffff81bf1b05: ima_read_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t ima_read_policy(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:274
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
```
**Symbols:**

```
ffffffff81539ba0-ffffffff81539cbe: ima_read_policy (STB_LOCAL)
ffffffff81be3b0a-ffffffff81be3b23: ima_read_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t ima_read_policy(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:274
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
```
**Symbols:**

```
ffffffff81598510-ffffffff8159862b: ima_read_policy (STB_LOCAL)
ffffffff81cd6cce-ffffffff81cd6ce7: ima_read_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t ima_read_policy(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_fs.c (0)
Location: security/integrity/ima/ima_fs.c:274
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
```
**Symbols:**

```
ffffffff8163cdd0-ffffffff8163cf10: ima_read_policy (STB_LOCAL)
ffffffff81e89f01-ffffffff81e89f1a: ima_read_policy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t ima_read_policy(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_fs.c (ffffffff816f47c0)
Location: security/integrity/ima/ima_fs.c:274
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
```
**Symbols:**

```
ffffffff816f47c0-ffffffff816f491c: ima_read_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t ima_read_policy(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_fs.c (ffffffff8172e8e0)
Location: security/integrity/ima/ima_fs.c:274
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
```
**Symbols:**

```
ffffffff8172e8e0-ffffffff8172ea2a: ima_read_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t ima_read_policy(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_fs.c (ffffffff8176f240)
Location: security/integrity/ima/ima_fs.c:274
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
```
**Symbols:**

```
ffffffff8176f240-ffffffff8176f38a: ima_read_policy (STB_LOCAL)
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
In security/integrity/ima/ima_fs.c (ffff8000105ad574)
Location: security/integrity/ima/ima_fs.c:275
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
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
In security/integrity/ima/ima_fs.c (c075cebc)
Location: security/integrity/ima/ima_fs.c:275
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
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
In security/integrity/ima/ima_fs.c (c00000000072c070)
Location: security/integrity/ima/ima_fs.c:275
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
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
In security/integrity/ima/ima_fs.c (ffffffe0003f5bba)
Location: security/integrity/ima/ima_fs.c:275
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
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
In security/integrity/ima/ima_fs.c (ffffffff814ad904)
Location: security/integrity/ima/ima_fs.c:275
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
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
In security/integrity/ima/ima_fs.c (ffffffff8149e324)
Location: security/integrity/ima/ima_fs.c:275
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
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
In security/integrity/ima/ima_fs.c (ffffffff814a99a4)
Location: security/integrity/ima/ima_fs.c:275
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
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
In security/integrity/ima/ima_fs.c (ffffffff814c2334)
Location: security/integrity/ima/ima_fs.c:275
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
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
