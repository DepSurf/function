# Function: <code>avtab_read_item</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff8134f9f0)
Location: security/selinux/ss/avtab.c:389
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff8134f9f0-ffffffff8134ff73: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81385a30)
Location: security/selinux/ss/avtab.c:389
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff81385a30-ffffffff81385fbe: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff8139c4c0)
Location: security/selinux/ss/avtab.c:389
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff8139c4c0-ffffffff8139ca4e: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff813b2bf0)
Location: security/selinux/ss/avtab.c:389
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff813b2bf0-ffffffff813b318f: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff813d8d30)
Location: security/selinux/ss/avtab.c:389
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff813d8d30-ffffffff813d92d3: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:389
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff81409a7f-ffffffff81409b7a: avtab_read_item.cold.6 (STB_LOCAL)
ffffffff81409320-ffffffff814097dd: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:389
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff81425d62-ffffffff81425e5d: avtab_read_item.cold.4 (STB_LOCAL)
ffffffff81425660-ffffffff81425b1d: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:387
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff8145376d-ffffffff81453897: avtab_read_item.cold (STB_LOCAL)
ffffffff81453110-ffffffff8145354f: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:387
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff8146d50d-ffffffff8146d637: avtab_read_item.cold (STB_LOCAL)
ffffffff8146ceb0-ffffffff8146d2ef: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:386
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff814c1cfd-ffffffff814c1e23: avtab_read_item.cold (STB_LOCAL)
ffffffff814c1680-ffffffff814c1ad5: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:433
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff81bf0734-ffffffff81bf085a: avtab_read_item.cold (STB_LOCAL)
ffffffff814df2b0-ffffffff814df705: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:398
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff81be2881-ffffffff81be29a7: avtab_read_item.cold (STB_LOCAL)
ffffffff814e5bb0-ffffffff814e600c: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, const struct avtab_key *, const struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:400
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff81cd43be-ffffffff81cd44e4: avtab_read_item.cold (STB_LOCAL)
ffffffff8153f2b0-ffffffff8153f86c: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, const struct avtab_key *, const struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:400
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff81e87340-ffffffff81e87416: avtab_read_item.cold (STB_LOCAL)
ffffffff815d6f80-ffffffff815d75b9: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, const struct avtab_key *, const struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff81685450)
Location: security/selinux/ss/avtab.c:400
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff81685450-ffffffff81685b08: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, const struct avtab_key *, const struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff816bd7b0)
Location: security/selinux/ss/avtab.c:400
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff816bd7b0-ffffffff816bde68: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, const struct avtab_key *, const struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffff816fa060)
Location: security/selinux/ss/avtab.c:340
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff816fa060-ffffffff816fa716: avtab_read_item (STB_GLOBAL)
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
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffff80001055bfc0)
Location: security/selinux/ss/avtab.c:387
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffff80001055bfc0-ffff80001055c454: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (c0710710)
Location: security/selinux/ss/avtab.c:387
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
c0710710-c0710bf4: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (c0000000006bb560)
Location: security/selinux/ss/avtab.c:387
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
c0000000006bb560-c0000000006bbb48: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/avtab.c (ffffffe0003b2cd4)
Location: security/selinux/ss/avtab.c:387
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffe0003b2cd4-ffffffe0003b314a: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:387
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff81465aed-ffffffff81465c17: avtab_read_item.cold (STB_LOCAL)
ffffffff81465490-ffffffff814658cf: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:387
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff8145651d-ffffffff81456647: avtab_read_item.cold (STB_LOCAL)
ffffffff81455ec0-ffffffff814562ff: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:387
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff81461b8d-ffffffff81461cb7: avtab_read_item.cold (STB_LOCAL)
ffffffff81461530-ffffffff8146196f: avtab_read_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int avtab_read_item(struct avtab *a, void *fp, struct policydb *pol, int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *), void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/avtab.c (0)
Location: security/selinux/ss/avtab.c:387
Inline: False
Direct callers:
  - security/selinux/ss/avtab.c:avtab_read
  - security/selinux/ss/conditional.c:cond_read_av_list
```
**Symbols:**

```
ffffffff8147938d-ffffffff814794b7: avtab_read_item.cold (STB_LOCAL)
ffffffff81478d30-ffffffff8147916f: avtab_read_item (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*insertf)(struct avtab *, struct avtab_key *, struct avtab_datum *, void *)</code> ➡️ <code>int (*insertf)(struct avtab *, const struct avtab_key *, const struct avtab_datum *, void *)</code>
</li>
</ul>
</details>
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
