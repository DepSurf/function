# Function: <code>security_dentry_create_files_as</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81387300)
Location: security/security.c:367
Inline: False
```
**Symbols:**

```
ffffffff81387300-ffffffff8138737b: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139bfe0)
Location: security/security.c:972
Inline: False
```
**Symbols:**

```
ffffffff8139bfe0-ffffffff8139c05b: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c16f0)
Location: security/security.c:921
Inline: False
```
**Symbols:**

```
ffffffff813c16f0-ffffffff813c1771: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2610)
Location: security/security.c:463
Inline: False
```
**Symbols:**

```
ffffffff813f2610-ffffffff813f2678: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140dab0)
Location: security/security.c:984
Inline: False
```
**Symbols:**

```
ffffffff8140dab0-ffffffff8140db18: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143aca0)
Location: security/security.c:998
Inline: False
```
**Symbols:**

```
ffffffff8143aca0-ffffffff8143ad19: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81454ab0)
Location: security/security.c:1038
Inline: False
```
**Symbols:**

```
ffffffff81454ab0-ffffffff81454b18: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a7440)
Location: security/security.c:1186
Inline: False
```
**Symbols:**

```
ffffffff814a7440-ffffffff814a74a8: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c49c0)
Location: security/security.c:1188
Inline: False
```
**Symbols:**

```
ffffffff814c49c0-ffffffff814c4a28: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814caeb0)
Location: security/security.c:1233
Inline: False
```
**Symbols:**

```
ffffffff814caeb0-ffffffff814caf18: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81523bb0)
Location: security/security.c:1233
Inline: False
```
**Symbols:**

```
ffffffff81523bb0-ffffffff81523c18: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b7920)
Location: security/security.c:1253
Inline: False
```
**Symbols:**

```
ffffffff815b7920-ffffffff815b79b7: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81662cc0)
Location: security/security.c:1251
Inline: False
```
**Symbols:**

```
ffffffff81662cc0-ffffffff81662d57: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169b1c0)
Location: security/security.c:1726
Inline: False
```
**Symbols:**

```
ffffffff8169b1c0-ffffffff8169b257: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d7c10)
Location: security/security.c:1775
Inline: False
```
**Symbols:**

```
ffffffff816d7c10-ffffffff816d7ca7: security_dentry_create_files_as (STB_GLOBAL)
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
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff80001053fcb0)
Location: security/security.c:1038
Inline: False
```
**Symbols:**

```
ffff80001053fcb0-ffff80001053fd30: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f5d70)
Location: security/security.c:1038
Inline: False
```
**Symbols:**

```
c06f5d70-c06f5dec: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000690fd0)
Location: security/security.c:1038
Inline: False
```
**Symbols:**

```
c000000000690fd0-c0000000006910c8: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039d010)
Location: security/security.c:1038
Inline: False
```
**Symbols:**

```
ffffffe00039d010-ffffffe00039d06c: security_dentry_create_files_as (STB_GLOBAL)
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
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144d090)
Location: security/security.c:1038
Inline: False
```
**Symbols:**

```
ffffffff8144d090-ffffffff8144d0f8: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143dae0)
Location: security/security.c:1038
Inline: False
```
**Symbols:**

```
ffffffff8143dae0-ffffffff8143db48: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81449130)
Location: security/security.c:1038
Inline: False
```
**Symbols:**

```
ffffffff81449130-ffffffff81449198: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81460500)
Location: security/security.c:1038
Inline: False
```
**Symbols:**

```
ffffffff81460500-ffffffff81460568: security_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
