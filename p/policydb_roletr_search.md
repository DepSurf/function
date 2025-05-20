# Function: <code>policydb_roletr_search</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct role_trans_datum *policydb_roletr_search(struct policydb *p, struct role_trans_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e37f0)
Location: security/selinux/ss/policydb.c:523
Inline: False
```
**Symbols:**

```
ffffffff814e37f0-ffffffff814e386b: policydb_roletr_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct role_trans_datum *policydb_roletr_search(struct policydb *p, struct role_trans_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814ea1b0)
Location: security/selinux/ss/policydb.c:523
Inline: False
```
**Symbols:**

```
ffffffff814ea1b0-ffffffff814ea224: policydb_roletr_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct role_trans_datum *policydb_roletr_search(struct policydb *p, struct role_trans_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81543b20)
Location: security/selinux/ss/policydb.c:523
Inline: False
```
**Symbols:**

```
ffffffff81543b20-ffffffff81543b94: policydb_roletr_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct role_trans_datum *policydb_roletr_search(struct policydb *p, struct role_trans_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff815dc3e0)
Location: security/selinux/ss/policydb.c:518
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_sid
```
**Symbols:**

```
ffffffff815dc3e0-ffffffff815dc47a: policydb_roletr_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct role_trans_datum *policydb_roletr_search(struct policydb *p, struct role_trans_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8168aee0)
Location: security/selinux/ss/policydb.c:518
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_sid
```
**Symbols:**

```
ffffffff8168aee0-ffffffff8168af7a: policydb_roletr_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct role_trans_datum *policydb_roletr_search(struct policydb *p, struct role_trans_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c3250)
Location: security/selinux/ss/policydb.c:518
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_sid
```
**Symbols:**

```
ffffffff816c3250-ffffffff816c32ea: policydb_roletr_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct role_trans_datum *policydb_roletr_search(struct policydb *p, struct role_trans_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816ffce0)
Location: security/selinux/ss/policydb.c:511
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_compute_sid
```
**Symbols:**

```
ffffffff816ffce0-ffffffff816ffd7b: policydb_roletr_search (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
