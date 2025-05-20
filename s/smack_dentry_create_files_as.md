# Function: <code>smack_dentry_create_files_as</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813e7770)
Location: security/smack/smack_lsm.c:4443
Inline: False
```
**Symbols:**

```
ffffffff813e7770-ffffffff813e77e6: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81418650)
Location: security/smack/smack_lsm.c:4611
Inline: False
```
**Symbols:**

```
ffffffff81418650-ffffffff814186aa: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81434c70)
Location: security/smack/smack_lsm.c:4442
Inline: False
```
**Symbols:**

```
ffffffff81434c70-ffffffff81434cdc: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814626c0)
Location: security/smack/smack_lsm.c:4541
Inline: False
```
**Symbols:**

```
ffffffff814626c0-ffffffff81462731: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8147c470)
Location: security/smack/smack_lsm.c:4538
Inline: False
```
**Symbols:**

```
ffffffff8147c470-ffffffff8147c4e1: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814d1e70)
Location: security/smack/smack_lsm.c:4612
Inline: False
```
**Symbols:**

```
ffffffff814d1e70-ffffffff814d1ee1: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814ef310)
Location: security/smack/smack_lsm.c:4655
Inline: False
```
**Symbols:**

```
ffffffff814ef310-ffffffff814ef392: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f63a0)
Location: security/smack/smack_lsm.c:4656
Inline: False
```
**Symbols:**

```
ffffffff814f63a0-ffffffff814f6422: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81550ef0)
Location: security/smack/smack_lsm.c:4656
Inline: False
```
**Symbols:**

```
ffffffff81550ef0-ffffffff81550f72: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815ea570)
Location: security/smack/smack_lsm.c:4665
Inline: False
```
**Symbols:**

```
ffffffff815ea570-ffffffff815ea608: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8169a0d0)
Location: security/smack/smack_lsm.c:4734
Inline: False
```
**Symbols:**

```
ffffffff8169a0d0-ffffffff8169a168: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d28b0)
Location: security/smack/smack_lsm.c:4797
Inline: False
```
**Symbols:**

```
ffffffff816d28b0-ffffffff816d294d: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8170ef90)
Location: security/smack/smack_lsm.c:4955
Inline: False
```
**Symbols:**

```
ffffffff8170ef90-ffffffff8170f033: smack_dentry_create_files_as (STB_LOCAL)
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
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffff80001056d1c0)
Location: security/smack/smack_lsm.c:4538
Inline: False
```
**Symbols:**

```
ffff80001056d1c0-ffff80001056d260: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c072097c)
Location: security/smack/smack_lsm.c:4538
Inline: False
```
**Symbols:**

```
c072097c-c0720a0c: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0000000006d1710)
Location: security/smack/smack_lsm.c:4538
Inline: False
```
**Symbols:**

```
c0000000006d1710-c0000000006d1804: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffe0003c1a7a)
Location: security/smack/smack_lsm.c:4538
Inline: False
```
**Symbols:**

```
ffffffe0003c1a7a-ffffffe0003c1b00: smack_dentry_create_files_as (STB_LOCAL)
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
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81474a50)
Location: security/smack/smack_lsm.c:4538
Inline: False
```
**Symbols:**

```
ffffffff81474a50-ffffffff81474ac1: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81465470)
Location: security/smack/smack_lsm.c:4538
Inline: False
```
**Symbols:**

```
ffffffff81465470-ffffffff814654e1: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81470af0)
Location: security/smack/smack_lsm.c:4538
Inline: False
```
**Symbols:**

```
ffffffff81470af0-ffffffff81470b61: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int smack_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814882d0)
Location: security/smack/smack_lsm.c:4538
Inline: False
```
**Symbols:**

```
ffffffff814882d0-ffffffff81488359: smack_dentry_create_files_as (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
