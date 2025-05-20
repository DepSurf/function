# Function: <code>context_read_and_validate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8139bc96)
Location: security/selinux/ss/policydb.c:1052
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8139bc96-ffffffff8139bd9b: context_read_and_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813d8af6)
Location: security/selinux/ss/policydb.c:1052
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff813d8af6-ffffffff813d8bfb: context_read_and_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813f063a)
Location: security/selinux/ss/policydb.c:1052
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff813f063a-ffffffff813f073f: context_read_and_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b8495)
Location: security/selinux/ss/policydb.c:1054
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff813b8495-ffffffff813b85ba: context_read_and_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813de60b)
Location: security/selinux/ss/policydb.c:1054
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff813de60b-ffffffff813de730: context_read_and_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8140df0f)
Location: security/selinux/ss/policydb.c:1054
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8140df0f-ffffffff8140e034: context_read_and_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8142afb8)
Location: security/selinux/ss/policydb.c:1065
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814291e0-ffffffff814292ac: context_read_and_validate (STB_LOCAL)
ffffffff8142afb8-ffffffff8142b029: context_read_and_validate.cold.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814588f3)
Location: security/selinux/ss/policydb.c:1017
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
ffffffff81456b70-ffffffff81456bf5: context_read_and_validate (STB_LOCAL)
ffffffff814588dc-ffffffff81458964: context_read_and_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81472693)
Location: security/selinux/ss/policydb.c:1019
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
ffffffff81470910-ffffffff81470995: context_read_and_validate (STB_LOCAL)
ffffffff8147267c-ffffffff81472704: context_read_and_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1005
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
ffffffff814c5d50-ffffffff814c5e09: context_read_and_validate (STB_LOCAL)
ffffffff814c7902-ffffffff814c7949: context_read_and_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1037
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
ffffffff814e3d90-ffffffff814e3e49: context_read_and_validate (STB_LOCAL)
ffffffff81bf0b0d-ffffffff81bf0b54: context_read_and_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1035
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
ffffffff814ea750-ffffffff814ea809: context_read_and_validate (STB_LOCAL)
ffffffff81be2c6c-ffffffff81be2cb3: context_read_and_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1035
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
ffffffff81544170-ffffffff81544229: context_read_and_validate (STB_LOCAL)
ffffffff81cd47a9-ffffffff81cd47f0: context_read_and_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1029
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
ffffffff815dcaa0-ffffffff815dcb60: context_read_and_validate (STB_LOCAL)
ffffffff81e87693-ffffffff81e876d1: context_read_and_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8168b670)
Location: security/selinux/ss/policydb.c:1029
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
ffffffff8168b670-ffffffff8168b7ca: context_read_and_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c39e0)
Location: security/selinux/ss/policydb.c:1029
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
ffffffff816c39e0-ffffffff816c3b3a: context_read_and_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff817004e0)
Location: security/selinux/ss/policydb.c:1050
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
ffffffff817004e0-ffffffff8170063a: context_read_and_validate (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffff800010560060)
Location: security/selinux/ss/policydb.c:1019
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
ffff800010560060-ffff800010560164: context_read_and_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c07147d0)
Location: security/selinux/ss/policydb.c:1019
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
c07147d0-c0714928: context_read_and_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0000000006c0c70)
Location: security/selinux/ss/policydb.c:1019
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
c0000000006c0c70-c0000000006c0dc8: context_read_and_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffe0003b6ab8)
Location: security/selinux/ss/policydb.c:1019
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffe0003b6ab8-ffffffe0003b6bd8: context_read_and_validate (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8146ac73)
Location: security/selinux/ss/policydb.c:1019
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
ffffffff81468ef0-ffffffff81468f75: context_read_and_validate (STB_LOCAL)
ffffffff8146ac5c-ffffffff8146ace4: context_read_and_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8145b6a3)
Location: security/selinux/ss/policydb.c:1019
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
ffffffff81459920-ffffffff814599a5: context_read_and_validate (STB_LOCAL)
ffffffff8145b68c-ffffffff8145b714: context_read_and_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81466d13)
Location: security/selinux/ss/policydb.c:1019
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
ffffffff81464f90-ffffffff81465015: context_read_and_validate (STB_LOCAL)
ffffffff81466cfc-ffffffff81466d84: context_read_and_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int context_read_and_validate(struct context *c, struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8147e4f3)
Location: security/selinux/ss/policydb.c:1019
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
```
**Symbols:**

```
ffffffff8147c770-ffffffff8147c7f5: context_read_and_validate (STB_LOCAL)
ffffffff8147e4dc-ffffffff8147e564: context_read_and_validate.cold (STB_LOCAL)
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
