# Function: <code>match_exception</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff813954a0)
Location: security/device_cgroup.c:322
Inline: False
Direct callers:
  - security/device_cgroup.c:verify_new_ex
  - security/device_cgroup.c:__devcgroup_check_permission
```
**Symbols:**

```
ffffffff813954a0-ffffffff8139551e: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff813d1200)
Location: security/device_cgroup.c:322
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_check_permission
  - security/device_cgroup.c:verify_new_ex
```
**Symbols:**

```
ffffffff813d1200-ffffffff813d127e: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff813e8930)
Location: security/device_cgroup.c:322
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_check_permission
  - security/device_cgroup.c:verify_new_ex
```
**Symbols:**

```
ffffffff813e8930-ffffffff813e89ae: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff813f4cd0)
Location: security/device_cgroup.c:322
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_check_permission
  - security/device_cgroup.c:verify_new_ex
```
**Symbols:**

```
ffffffff813f4cd0-ffffffff813f4d4c: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff8141cee0)
Location: security/device_cgroup.c:314
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_check_permission
  - security/device_cgroup.c:verify_new_ex
```
**Symbols:**

```
ffffffff8141cee0-ffffffff8141cf5c: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff8144f1a0)
Location: security/device_cgroup.c:314
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_check_permission
  - security/device_cgroup.c:verify_new_ex
```
**Symbols:**

```
ffffffff8144f1a0-ffffffff8144f21c: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff8146c180)
Location: security/device_cgroup.c:314
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_check_permission
  - security/device_cgroup.c:verify_new_ex
```
**Symbols:**

```
ffffffff8146c180-ffffffff8146c1fc: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81499860)
Location: security/device_cgroup.c:313
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_check_permission
  - security/device_cgroup.c:verify_new_ex
```
**Symbols:**

```
ffffffff81499860-ffffffff814998dc: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff814b3a60)
Location: security/device_cgroup.c:313
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_check_permission
  - security/device_cgroup.c:verify_new_ex
```
**Symbols:**

```
ffffffff814b3a60-ffffffff814b3adc: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81512f90)
Location: security/device_cgroup.c:315
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_check_permission
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:revalidate_active_exceptions
```
**Symbols:**

```
ffffffff81512f90-ffffffff81513009: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff815300e0)
Location: security/device_cgroup.c:315
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_check_permission
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:revalidate_active_exceptions
```
**Symbols:**

```
ffffffff815300e0-ffffffff81530159: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff815362e0)
Location: security/device_cgroup.c:315
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_check_permission
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:propagate_exception
```
**Symbols:**

```
ffffffff815362e0-ffffffff81536359: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81594a10)
Location: security/device_cgroup.c:315
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_check_permission
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:propagate_exception
```
**Symbols:**

```
ffffffff81594a10-ffffffff81594a89: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81636b10)
Location: security/device_cgroup.c:316
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_check_permission
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:propagate_exception
```
**Symbols:**

```
ffffffff81636b10-ffffffff81636bb3: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff816edcc0)
Location: security/device_cgroup.c:327
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_check_permission
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:propagate_exception
```
**Symbols:**

```
ffffffff816edcc0-ffffffff816edd63: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff817280d0)
Location: security/device_cgroup.c:327
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_check_permission
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:propagate_exception
```
**Symbols:**

```
ffffffff817280d0-ffffffff81728186: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81769400)
Location: security/device_cgroup.c:327
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_check_permission
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:propagate_exception
```
**Symbols:**

```
ffffffff81769400-ffffffff817694b6: match_exception (STB_LOCAL)
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
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffff8000105ab7b8)
Location: security/device_cgroup.c:313
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_check_permission
  - security/device_cgroup.c:verify_new_ex
```
**Symbols:**

```
ffff8000105ab7b8-ffff8000105ab884: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (c075b35c)
Location: security/device_cgroup.c:313
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_check_permission
  - security/device_cgroup.c:verify_new_ex
```
**Symbols:**

```
c075b35c-c075b400: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (c000000000729890)
Location: security/device_cgroup.c:313
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_check_permission
  - security/device_cgroup.c:verify_new_ex
```
**Symbols:**

```
c000000000729890-c000000000729938: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffe0003f42c6)
Location: security/device_cgroup.c:313
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_check_permission
  - security/device_cgroup.c:verify_new_ex
```
**Symbols:**

```
ffffffe0003f42c6-ffffffe0003f435e: match_exception (STB_LOCAL)
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
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff814ac040)
Location: security/device_cgroup.c:313
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_check_permission
  - security/device_cgroup.c:verify_new_ex
```
**Symbols:**

```
ffffffff814ac040-ffffffff814ac0bc: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff8149ca60)
Location: security/device_cgroup.c:313
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_check_permission
  - security/device_cgroup.c:verify_new_ex
```
**Symbols:**

```
ffffffff8149ca60-ffffffff8149cadc: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff814a80e0)
Location: security/device_cgroup.c:313
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_check_permission
  - security/device_cgroup.c:verify_new_ex
```
**Symbols:**

```
ffffffff814a80e0-ffffffff814a815c: match_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool match_exception(struct list_head *exceptions, short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff814c0a70)
Location: security/device_cgroup.c:313
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_check_permission
  - security/device_cgroup.c:verify_new_ex
```
**Symbols:**

```
ffffffff814c0a70-ffffffff814c0aec: match_exception (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
