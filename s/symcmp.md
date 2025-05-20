# Function: <code>symcmp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff8134e730)
Location: security/selinux/ss/symtab.c:25
Inline: False
```
**Symbols:**

```
ffffffff8134e730-ffffffff8134e746: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff81384720)
Location: security/selinux/ss/symtab.c:25
Inline: False
```
**Symbols:**

```
ffffffff81384720-ffffffff81384736: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff8139b1b0)
Location: security/selinux/ss/symtab.c:25
Inline: False
```
**Symbols:**

```
ffffffff8139b1b0-ffffffff8139b1c6: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff813b18d0)
Location: security/selinux/ss/symtab.c:25
Inline: False
```
**Symbols:**

```
ffffffff813b18d0-ffffffff813b18e6: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff813d7a10)
Location: security/selinux/ss/symtab.c:26
Inline: False
```
**Symbols:**

```
ffffffff813d7a10-ffffffff813d7a26: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff81408040)
Location: security/selinux/ss/symtab.c:26
Inline: False
```
**Symbols:**

```
ffffffff81408040-ffffffff81408056: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff81423ba0)
Location: security/selinux/ss/symtab.c:26
Inline: False
```
**Symbols:**

```
ffffffff81423ba0-ffffffff81423bb6: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff81451700)
Location: security/selinux/ss/symtab.c:26
Inline: False
```
**Symbols:**

```
ffffffff81451700-ffffffff81451716: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff8146b4e0)
Location: security/selinux/ss/symtab.c:26
Inline: False
```
**Symbols:**

```
ffffffff8146b4e0-ffffffff8146b4f6: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff814bfa40)
Location: security/selinux/ss/symtab.c:26
Inline: False
```
**Symbols:**

```
ffffffff814bfa40-ffffffff814bfa56: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int symcmp(const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff814dd547)
Location: security/selinux/ss/symtab.c:26
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_search
  - security/selinux/ss/symtab.c:symtab_insert
```
**Symbols:**

```
ffffffff814dd3b0-ffffffff814dd3c0: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int symcmp(const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff814e3eb7)
Location: security/selinux/ss/symtab.c:26
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_search
  - security/selinux/ss/symtab.c:symtab_insert
```
**Symbols:**

```
ffffffff814e3d20-ffffffff814e3d30: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int symcmp(const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff8153d2d7)
Location: security/selinux/ss/symtab.c:26
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_search
  - security/selinux/ss/symtab.c:symtab_insert
```
**Symbols:**

```
ffffffff8153d140-ffffffff8153d150: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int symcmp(const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff815d4d82)
Location: security/selinux/ss/symtab.c:26
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_search
  - security/selinux/ss/symtab.c:symtab_insert
```
**Symbols:**

```
ffffffff815d4bb0-ffffffff815d4bc8: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int symcmp(const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff81682f42)
Location: security/selinux/ss/symtab.c:26
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_search
  - security/selinux/ss/symtab.c:symtab_insert
```
**Symbols:**

```
ffffffff81682d30-ffffffff81682d48: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int symcmp(const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff816bb0c2)
Location: security/selinux/ss/symtab.c:26
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_search
  - security/selinux/ss/symtab.c:symtab_insert
```
**Symbols:**

```
ffffffff816baeb0-ffffffff816baec8: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int symcmp(const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff816f7ac2)
Location: security/selinux/ss/symtab.c:26
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_search
  - security/selinux/ss/symtab.c:symtab_insert
```
**Symbols:**

```
ffffffff816f78b0-ffffffff816f78c8: symcmp (STB_LOCAL)
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
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffff80001055a2b8)
Location: security/selinux/ss/symtab.c:26
Inline: False
```
**Symbols:**

```
ffff80001055a2b8-ffff80001055a2ec: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (c070eb08)
Location: security/selinux/ss/symtab.c:26
Inline: False
```
**Symbols:**

```
c070eb08-c070eb2c: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (c0000000006b8850)
Location: security/selinux/ss/symtab.c:26
Inline: False
```
**Symbols:**

```
c0000000006b8850-c0000000006b89d8: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffe0003b1332)
Location: security/selinux/ss/symtab.c:26
Inline: False
```
**Symbols:**

```
ffffffe0003b1332-ffffffe0003b1364: symcmp (STB_LOCAL)
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
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff81463ac0)
Location: security/selinux/ss/symtab.c:26
Inline: False
```
**Symbols:**

```
ffffffff81463ac0-ffffffff81463ad6: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff814544f0)
Location: security/selinux/ss/symtab.c:26
Inline: False
```
**Symbols:**

```
ffffffff814544f0-ffffffff81454506: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff8145fb60)
Location: security/selinux/ss/symtab.c:26
Inline: False
```
**Symbols:**

```
ffffffff8145fb60-ffffffff8145fb76: symcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int symcmp(struct hashtab *h, const void *key1, const void *key2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/symtab.c (ffffffff81477370)
Location: security/selinux/ss/symtab.c:26
Inline: False
```
**Symbols:**

```
ffffffff81477370-ffffffff81477386: symcmp (STB_LOCAL)
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
<code>h, key1, key2</code> ➡️ <code>key1, key2</code>
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
