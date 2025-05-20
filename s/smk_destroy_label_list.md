# Function: <code>smk_destroy_label_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81365172)
Location: security/smack/smackfs.c:2014
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
Direct callers:
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
```
**Symbols:**

```
ffffffff81366120-ffffffff8136615b: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8139b125)
Location: security/smack/smackfs.c:1983
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff8139c200-ffffffff8139c23b: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813b1e15)
Location: security/smack/smackfs.c:1983
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff813b2db0-ffffffff813b2deb: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813c83fa)
Location: security/smack/smackfs.c:1988
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff813c9740-ffffffff813c977b: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813ee88a)
Location: security/smack/smackfs.c:1988
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff813efbd0-ffffffff813efc0b: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8141f953)
Location: security/smack/smackfs.c:1988
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff814208b0-ffffffff814208eb: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8143a761)
Location: security/smack/smackfs.c:1988
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff8143cf00-ffffffff8143cf3b: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff814683ad)
Location: security/smack/smackfs.c:1960
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff8146aaa0-ffffffff8146aad8: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8148218d)
Location: security/smack/smackfs.c:1960
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff81484880-ffffffff814848b8: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff814da277)
Location: security/smack/smackfs.c:1979
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff814da9d0-ffffffff814daa08: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff814f7837)
Location: security/smack/smackfs.c:1987
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff814f7fa0-ffffffff814f7fd8: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff814fec86)
Location: security/smack/smackfs.c:1989
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff814fed00-ffffffff814fed38: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81559cd6)
Location: security/smack/smackfs.c:1990
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff81559d50-ffffffff81559d88: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff815f49b7)
Location: security/smack/smackfs.c:1989
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff815f4a40-ffffffff815f4a7e: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff816a5437)
Location: security/smack/smackfs.c:1989
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff816a54d0-ffffffff816a550e: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff816dde17)
Location: security/smack/smackfs.c:2000
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff816ddeb0-ffffffff816ddeee: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8171a93a)
Location: security/smack/smackfs.c:2012
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:do_setattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff8171a9d0-ffffffff8171aa0e: smk_destroy_label_list (STB_GLOBAL)
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
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffff800010574048)
Location: security/smack/smackfs.c:1960
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffff800010576e58-ffff800010576ea8: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (c07270b0)
Location: security/smack/smackfs.c:1960
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
c0729c5c-c0729ca4: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (c0000000006df29c)
Location: security/smack/smackfs.c:1960
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
c0000000006e0260-c0000000006e02d8: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffe0003c7248)
Location: security/smack/smackfs.c:1960
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffe0003c93e8-ffffffe0003c942e: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8147a76d)
Location: security/smack/smackfs.c:1960
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff8147ce60-ffffffff8147ce98: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8146b18d)
Location: security/smack/smackfs.c:1960
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff8146d880-ffffffff8146d8b8: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8147680d)
Location: security/smack/smackfs.c:1960
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff81478f00-ffffffff81478f38: smk_destroy_label_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void smk_destroy_label_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8148e2bd)
Location: security/smack/smackfs.c:1960
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_onlycap
Direct callers:
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
```
**Symbols:**

```
ffffffff814909b0-ffffffff814909e8: smk_destroy_label_list (STB_GLOBAL)
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
