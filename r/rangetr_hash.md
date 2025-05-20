# Function: <code>rangetr_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81350300)
Location: security/selinux/ss/policydb.c:244
Inline: False
```
**Symbols:**

```
ffffffff81350300-ffffffff81350323: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81386340)
Location: security/selinux/ss/policydb.c:244
Inline: False
```
**Symbols:**

```
ffffffff81386340-ffffffff81386361: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8139cdd0)
Location: security/selinux/ss/policydb.c:244
Inline: False
```
**Symbols:**

```
ffffffff8139cdd0-ffffffff8139cdf1: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b3520)
Location: security/selinux/ss/policydb.c:253
Inline: False
```
**Symbols:**

```
ffffffff813b3520-ffffffff813b3541: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813d9670)
Location: security/selinux/ss/policydb.c:253
Inline: False
```
**Symbols:**

```
ffffffff813d9670-ffffffff813d9691: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81409c20)
Location: security/selinux/ss/policydb.c:253
Inline: False
```
**Symbols:**

```
ffffffff81409c20-ffffffff81409c41: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81425f10)
Location: security/selinux/ss/policydb.c:253
Inline: False
```
**Symbols:**

```
ffffffff81425f10-ffffffff81425f31: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81453950)
Location: security/selinux/ss/policydb.c:250
Inline: False
```
**Symbols:**

```
ffffffff81453950-ffffffff81453971: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8146d6f0)
Location: security/selinux/ss/policydb.c:439
Inline: False
```
**Symbols:**

```
ffffffff8146d6f0-ffffffff8146d711: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814c1ef0)
Location: security/selinux/ss/policydb.c:447
Inline: False
```
**Symbols:**

```
ffffffff814c1ef0-ffffffff814c1f11: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 rangetr_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e308c)
Location: security/selinux/ss/policydb.c:458
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:policydb_rangetr_search
```
**Symbols:**

```
ffffffff814df990-ffffffff814df9a9: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 rangetr_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e9904)
Location: security/selinux/ss/policydb.c:458
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:policydb_rangetr_search
```
**Symbols:**

```
ffffffff814e6290-ffffffff814e62a9: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u32 rangetr_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81543274)
Location: security/selinux/ss/policydb.c:458
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:policydb_rangetr_search
```
**Symbols:**

```
ffffffff8153fb20-ffffffff8153fb39: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u32 rangetr_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff815da873)
Location: security/selinux/ss/policydb.c:453
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:policydb_rangetr_search
```
**Symbols:**

```
ffffffff815d7940-ffffffff815d7961: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u32 rangetr_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81688fb3)
Location: security/selinux/ss/policydb.c:453
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:policydb_rangetr_search
```
**Symbols:**

```
ffffffff81685ee0-ffffffff81685f01: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u32 rangetr_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c2663)
Location: security/selinux/ss/policydb.c:453
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:policydb_rangetr_search
```
**Symbols:**

```
ffffffff816be250-ffffffff816be271: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u32 rangetr_hash(const void *k);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816ff1e1)
Location: security/selinux/ss/policydb.c:446
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:policydb_rangetr_search
```
**Symbols:**

```
ffffffff816faa90-ffffffff816faab1: rangetr_hash (STB_LOCAL)
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
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffff80001055c7e8)
Location: security/selinux/ss/policydb.c:439
Inline: False
```
**Symbols:**

```
ffff80001055c7e8-ffff80001055c830: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0710f90)
Location: security/selinux/ss/policydb.c:439
Inline: False
```
**Symbols:**

```
c0710f90-c0710fcc: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0000000006bbfe0)
Location: security/selinux/ss/policydb.c:439
Inline: False
```
**Symbols:**

```
c0000000006bbfe0-c0000000006bc018: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffe0003b34ca)
Location: security/selinux/ss/policydb.c:439
Inline: False
```
**Symbols:**

```
ffffffe0003b34ca-ffffffe0003b350e: rangetr_hash (STB_LOCAL)
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
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81465cd0)
Location: security/selinux/ss/policydb.c:439
Inline: False
```
**Symbols:**

```
ffffffff81465cd0-ffffffff81465cf1: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81456700)
Location: security/selinux/ss/policydb.c:439
Inline: False
```
**Symbols:**

```
ffffffff81456700-ffffffff81456721: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81461d70)
Location: security/selinux/ss/policydb.c:439
Inline: False
```
**Symbols:**

```
ffffffff81461d70-ffffffff81461d91: rangetr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 rangetr_hash(struct hashtab *h, const void *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81479570)
Location: security/selinux/ss/policydb.c:439
Inline: False
```
**Symbols:**

```
ffffffff81479570-ffffffff81479591: rangetr_hash (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct hashtab *h</code>
</li>
<li>
<b>Param reordered. </b>
<code>h, k</code> ➡️ <code>k</code>
</li>
</ul>
</details>
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
