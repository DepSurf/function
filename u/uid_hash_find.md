# Function: <code>uid_hash_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct user_struct *uid_hash_find(kuid_t uid, struct hlist_head *hashent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff8108c6d0)
Location: kernel/user.c:112
Inline: False
Direct callers:
  - kernel/user.c:find_user
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
```
**Symbols:**

```
ffffffff8108c6d0-ffffffff8108c703: uid_hash_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct user_struct *uid_hash_find(kuid_t uid, struct hlist_head *hashent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff8108f750)
Location: kernel/user.c:112
Inline: False
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff8108f750-ffffffff8108f780: uid_hash_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct user_struct *uid_hash_find(kuid_t uid, struct hlist_head *hashent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810946d0)
Location: kernel/user.c:112
Inline: False
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff810946d0-ffffffff81094700: uid_hash_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct user_struct *uid_hash_find(kuid_t uid, struct hlist_head *hashent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810917b0)
Location: kernel/user.c:113
Inline: False
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff810917b0-ffffffff810917e4: uid_hash_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct user_struct *uid_hash_find(kuid_t uid, struct hlist_head *hashent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff81098640)
Location: kernel/user.c:119
Inline: False
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff81098640-ffffffff81098680: uid_hash_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffffffff8109bd70)
Location: kernel/user.c:120
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff8109bd70-ffffffff8109bdb8: uid_hash_find.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffffffff810a3f60)
Location: kernel/user.c:120
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff810a3f60-ffffffff810a3fb1: uid_hash_find.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffffffff810a8c50)
Location: kernel/user.c:121
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff810a8c50-ffffffff810a8c84: uid_hash_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffffffff810af220)
Location: kernel/user.c:121
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff810af220-ffffffff810af254: uid_hash_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffffffff810b6f10)
Location: kernel/user.c:121
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff810b6f10-ffffffff810b6f89: uid_hash_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffffffff810b20d0)
Location: kernel/user.c:121
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff810b20d0-ffffffff810b2149: uid_hash_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffffffff810b3710)
Location: kernel/user.c:121
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff810b3710-ffffffff810b3789: uid_hash_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffffffff810c58b0)
Location: kernel/user.c:118
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff810c58b0-ffffffff810c5929: uid_hash_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffffffff810dce90)
Location: kernel/user.c:118
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff810dce90-ffffffff810dcf1a: uid_hash_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffffffff810fd250)
Location: kernel/user.c:118
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff810fd250-ffffffff810fd2da: uid_hash_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffffffff81109250)
Location: kernel/user.c:118
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff81109250-ffffffff81109305: uid_hash_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffffffff81112be0)
Location: kernel/user.c:131
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff81112be0-ffffffff81112c95: uid_hash_find.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffff80001010a210)
Location: kernel/user.c:121
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffff80001010a210-ffff80001010a27c: uid_hash_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct user_struct *uid_hash_find(kuid_t uid, struct hlist_head *hashent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (c0363344)
Location: kernel/user.c:121
Inline: False
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
c0363344-c0363398: uid_hash_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (c000000000151478)
Location: kernel/user.c:121
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffe0000ccf10)
Location: kernel/user.c:121
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffffffff810a9590)
Location: kernel/user.c:121
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff810a9590-ffffffff810a95c4: uid_hash_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffffffff81097f50)
Location: kernel/user.c:121
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff81097f50-ffffffff81097f84: uid_hash_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffffffff810a8af0)
Location: kernel/user.c:121
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff810a8af0-ffffffff810a8b24: uid_hash_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/user.c (ffffffff810b0c10)
Location: kernel/user.c:121
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
**Symbols:**

```
ffffffff810b0c10-ffffffff810b0c44: uid_hash_find.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
