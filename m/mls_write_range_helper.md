# Function: <code>mls_write_range_helper</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81350e20)
Location: security/selinux/ss/policydb.c:2544
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:user_write
  - security/selinux/ss/policydb.c:range_write_helper
```
**Symbols:**

```
ffffffff81350e20-ffffffff81350efd: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81386e80)
Location: security/selinux/ss/policydb.c:2544
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff81386e80-ffffffff81386f5d: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8139d930)
Location: security/selinux/ss/policydb.c:2548
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff8139d930-ffffffff8139da0d: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b4380)
Location: security/selinux/ss/policydb.c:2587
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff813b4380-ffffffff813b446a: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813da4d0)
Location: security/selinux/ss/policydb.c:2587
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff813da4d0-ffffffff813da5ba: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8140a880)
Location: security/selinux/ss/policydb.c:2587
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff8140a880-ffffffff8140a96a: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81426cf0)
Location: security/selinux/ss/policydb.c:2612
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff81426cf0-ffffffff81426dda: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814545c0)
Location: security/selinux/ss/policydb.c:2558
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff814545c0-ffffffff814546a6: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8146e360)
Location: security/selinux/ss/policydb.c:2560
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff8146e360-ffffffff8146e446: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814c2d70)
Location: security/selinux/ss/policydb.c:2702
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff814c2d70-ffffffff814c2e4d: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e08a0)
Location: security/selinux/ss/policydb.c:2744
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff814e08a0-ffffffff814e097d: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e8310)
Location: security/selinux/ss/policydb.c:2742
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff814e8310-ffffffff814e83ed: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81541c50)
Location: security/selinux/ss/policydb.c:2741
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff81541c50-ffffffff81541d2d: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff815d9f20)
Location: security/selinux/ss/policydb.c:2735
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff815d9f20-ffffffff815da064: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816869c0)
Location: security/selinux/ss/policydb.c:2735
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff816869c0-ffffffff81686aaf: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816bf580)
Location: security/selinux/ss/policydb.c:2739
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff816bf580-ffffffff816bf66f: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816fbdc0)
Location: security/selinux/ss/policydb.c:2764
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:genfs_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:ocontext_write
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff816fbdc0-ffffffff816fbeaf: mls_write_range_helper (STB_LOCAL)
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
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffff80001055da28)
Location: security/selinux/ss/policydb.c:2560
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffff80001055da28-ffff80001055db44: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0711dc0)
Location: security/selinux/ss/policydb.c:2560
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
c0711dc0-c0711efc: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0000000006bd700)
Location: security/selinux/ss/policydb.c:2560
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
c0000000006bd700-c0000000006bd86c: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffe0003b4110)
Location: security/selinux/ss/policydb.c:2560
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffe0003b4110-ffffffe0003b4272: mls_write_range_helper (STB_LOCAL)
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
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81466940)
Location: security/selinux/ss/policydb.c:2560
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff81466940-ffffffff81466a26: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81457370)
Location: security/selinux/ss/policydb.c:2560
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff81457370-ffffffff81457456: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814629e0)
Location: security/selinux/ss/policydb.c:2560
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff814629e0-ffffffff81462ac6: mls_write_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mls_write_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8147a1e0)
Location: security/selinux/ss/policydb.c:2560
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_write_helper
  - security/selinux/ss/policydb.c:user_write
```
**Symbols:**

```
ffffffff8147a1e0-ffffffff8147a2c6: mls_write_range_helper (STB_LOCAL)
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
