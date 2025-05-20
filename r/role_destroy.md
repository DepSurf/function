# Function: <code>role_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813504b0)
Location: security/selinux/ss/policydb.c:685
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff813504b0-ffffffff813504e6: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813864f0)
Location: security/selinux/ss/policydb.c:685
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff813864f0-ffffffff81386526: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8139cf80)
Location: security/selinux/ss/policydb.c:685
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff8139cf80-ffffffff8139cfb6: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b36d0)
Location: security/selinux/ss/policydb.c:689
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff813b36d0-ffffffff813b3706: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813d9820)
Location: security/selinux/ss/policydb.c:689
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff813d9820-ffffffff813d9856: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81409dd0)
Location: security/selinux/ss/policydb.c:689
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff81409dd0-ffffffff81409e06: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814260c0)
Location: security/selinux/ss/policydb.c:691
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff814260c0-ffffffff814260f6: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81453ca0)
Location: security/selinux/ss/policydb.c:652
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff81453ca0-ffffffff81453cda: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8146da40)
Location: security/selinux/ss/policydb.c:261
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff8146da40-ffffffff8146da7a: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814c3722)
Location: security/selinux/ss/policydb.c:260
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff814c21c0-ffffffff814c21fc: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e1252)
Location: security/selinux/ss/policydb.c:260
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff814dfc40-ffffffff814dfc7c: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e7722)
Location: security/selinux/ss/policydb.c:260
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff814e6500-ffffffff814e653c: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81540ce2)
Location: security/selinux/ss/policydb.c:260
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff8153fd90-ffffffff8153fdcc: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff815d904b)
Location: security/selinux/ss/policydb.c:256
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff815d7d60-ffffffff815d7da1: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81687db7)
Location: security/selinux/ss/policydb.c:256
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff816863d0-ffffffff81686411: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c115c)
Location: security/selinux/ss/policydb.c:256
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff816be740-ffffffff816be781: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816fdba5)
Location: security/selinux/ss/policydb.c:256
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff816faf90-ffffffff816fafd1: role_destroy (STB_LOCAL)
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
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffff80001055cc28)
Location: security/selinux/ss/policydb.c:261
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffff80001055cc28-ffff80001055cc78: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c071130c)
Location: security/selinux/ss/policydb.c:261
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
c071130c-c0711350: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0000000006bc540)
Location: security/selinux/ss/policydb.c:261
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
c0000000006bc540-c0000000006bc5b0: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffe0003b38ae)
Location: security/selinux/ss/policydb.c:261
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffe0003b38ae-ffffffe0003b3904: role_destroy (STB_LOCAL)
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
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81466020)
Location: security/selinux/ss/policydb.c:261
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff81466020-ffffffff8146605a: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81456a50)
Location: security/selinux/ss/policydb.c:261
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff81456a50-ffffffff81456a8a: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814620c0)
Location: security/selinux/ss/policydb.c:261
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff814620c0-ffffffff814620fa: role_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int role_destroy(void *key, void *datum, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814798c0)
Location: security/selinux/ss/policydb.c:261
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_read
```
**Symbols:**

```
ffffffff814798c0-ffffffff814798fa: role_destroy (STB_LOCAL)
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
