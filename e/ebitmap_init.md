# Function: <code>ebitmap_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8134d713)
Location: security/selinux/ss/ebitmap.h:59
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
  - security/selinux/ss/ebitmap.c:ebitmap_read
```
```
In security/selinux/ss/policydb.c (ffffffff81352957)
Location: security/selinux/ss/ebitmap.h:59
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/mls.c (ffffffff8135c537)
Location: security/selinux/ss/ebitmap.h:59
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81383ddc)
Location: security/selinux/ss/ebitmap.h:59
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff8138a419)
Location: security/selinux/ss/ebitmap.h:59
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/mls.c (ffffffff81392509)
Location: security/selinux/ss/ebitmap.h:59
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8139a85c)
Location: security/selinux/ss/ebitmap.h:59
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff813a102f)
Location: security/selinux/ss/ebitmap.h:59
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/mls.c (ffffffff813a9139)
Location: security/selinux/ss/ebitmap.h:59
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff813b0f25)
Location: security/selinux/ss/ebitmap.h:59
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff813b75a8)
Location: security/selinux/ss/ebitmap.h:59
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/mls.c (ffffffff813bfbdc)
Location: security/selinux/ss/ebitmap.h:59
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff813d7015)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff813dd710)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/mls.c (ffffffff813e5d7c)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81407665)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff8140e64a)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
```
In security/selinux/ss/mls.c (ffffffff81416975)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_convert_context
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814231b5)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff8142a5cb)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81450d65)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff8145762c)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8146ab45)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff814713cc)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ebitmap_init(struct ebitmap *e);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814befa5)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff814c6702)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814c2270-ffffffff814c2280: ebitmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ebitmap_init(struct ebitmap *e);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814dc9c5)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff814e4749)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814dfcd0-ffffffff814dfce0: ebitmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ebitmap_init(struct ebitmap *e);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814e3305)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff814eb102)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff814e6540-ffffffff814e6550: ebitmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ebitmap_init(struct ebitmap *e);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8153c6c5)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff81544b5a)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff8153fdd0-ffffffff8153fde0: ebitmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ebitmap_init(struct ebitmap *e);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff815d4057)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff815dd553)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff815d8130-ffffffff815d8146: ebitmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ebitmap_init(struct ebitmap *e);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81682137)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff8168c253)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81686b90-ffffffff81686ba6: ebitmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ebitmap_init(struct ebitmap *e);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff816ba2b7)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff816c45c3)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff816bf960-ffffffff816bf976: ebitmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ebitmap_init(struct ebitmap *e);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff816f6d47)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff81701119)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff816fc1a0-ffffffff816fc1b6: ebitmap_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffff800010559898)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffff800010560bac)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (c070e09c)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (c0715448)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (c0000000006b7a58)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (c0000000006c1d54)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffe0003b08b8)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffe0003b73d4)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81463125)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff814699ac)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81453b55)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff8145a3dc)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8145f1c5)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff81465a4c)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814769d5)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_read
  - security/selinux/ss/ebitmap.c:ebitmap_cpy
```
```
In security/selinux/ss/policydb.c (ffffffff8147d22c)
Location: security/selinux/ss/ebitmap.h:60
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
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
