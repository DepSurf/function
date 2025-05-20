# Function: <code>tomoyo_mount_acl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff81371360)
Location: security/tomoyo/mount.c:74
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff81371360-ffffffff813716be: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff813a7760)
Location: security/tomoyo/mount.c:74
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff813a7760-ffffffff813a7aca: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff813be2f0)
Location: security/tomoyo/mount.c:74
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff813be2f0-ffffffff813be65a: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff813d4ba0)
Location: security/tomoyo/mount.c:74
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff813d4ba0-ffffffff813d4f5e: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff813fb0b0)
Location: security/tomoyo/mount.c:75
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff813fb0b0-ffffffff813fb46e: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff8142c070)
Location: security/tomoyo/mount.c:75
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff8142c070-ffffffff8142c3d5: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff814489c0)
Location: security/tomoyo/mount.c:76
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff814489c0-ffffffff81448d25: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff81476620)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff81476620-ffffffff8147695a: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff814903c0)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff814903c0-ffffffff814906fa: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff814e7740)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff814e7740-ffffffff814e7a7a: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff81504ac0)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff81504ac0-ffffffff81504dfa: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff8150b640)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff8150b640-ffffffff8150b97a: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff81568eb0)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff81568eb0-ffffffff815691ea: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff81604bf0)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff81604bf0-ffffffff81604f5a: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff816b5f10)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff816b5f10-ffffffff816b627a: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff816ee920)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff816ee920-ffffffff816eec8a: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff8172b6f0)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff8172b6f0-ffffffff8172ba5a: tomoyo_mount_acl (STB_LOCAL)
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
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffff8000105845f8)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffff8000105845f8-ffff800010584950: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (c0736024)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
c0736024-c07363c0: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (c0000000006f3870)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
c0000000006f3870-c0000000006f3cf4: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffe0003d4582)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffe0003d4582-ffffffe0003d487a: tomoyo_mount_acl (STB_LOCAL)
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
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff814889a0)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff814889a0-ffffffff81488cda: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff814793c0)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff814793c0-ffffffff814796fa: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff81484a40)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff81484a40-ffffffff81484d7a: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tomoyo_mount_acl(struct tomoyo_request_info *r, const char *dev_name, const struct path *dir, const char *type, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff8149c580)
Location: security/tomoyo/mount.c:77
Inline: False
Direct callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
**Symbols:**

```
ffffffff8149c580-ffffffff8149c8ba: tomoyo_mount_acl (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *dir</code> ➡️ <code>const struct path *dir</code>
</li>
</ul>
</details>
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
