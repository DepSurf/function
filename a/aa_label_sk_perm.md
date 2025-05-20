# Function: <code>aa_label_sk_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_label_sk_perm(struct aa_label *label, const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813907f0)
Location: security/apparmor/net.c:193
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sock_file_perm
```
**Symbols:**

```
ffffffff813907f0-ffffffff813909b2: aa_label_sk_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_label_sk_perm(struct aa_label *label, const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813cbda0)
Location: security/apparmor/net.c:193
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff813cbda0-ffffffff813cbf48: aa_label_sk_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_label_sk_perm(struct aa_label *label, const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813e3420)
Location: security/apparmor/net.c:193
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff813e3420-ffffffff813e35c8: aa_label_sk_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_label_sk_perm(struct aa_label *label, const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813f18a0)
Location: security/apparmor/net.c:192
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff813f18a0-ffffffff813f19df: aa_label_sk_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_label_sk_perm(struct aa_label *label, const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814198c0)
Location: security/apparmor/net.c:192
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff814198c0-ffffffff814199ff: aa_label_sk_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_label_sk_perm(struct aa_label *label, const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8144bd20)
Location: security/apparmor/net.c:212
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff8144bd20-ffffffff8144be5e: aa_label_sk_perm (STB_LOCAL)
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
In security/apparmor/net.c (ffffffff81469095)
Location: security/apparmor/net.c:212
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff81468c90-ffffffff81468ddf: aa_label_sk_perm.part.5 (STB_LOCAL)
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
In security/apparmor/net.c (ffffffff814960e5)
Location: security/apparmor/net.c:208
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff81495cd0-ffffffff81495e22: aa_label_sk_perm.part.0 (STB_LOCAL)
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
In security/apparmor/net.c (ffffffff814b0015)
Location: security/apparmor/net.c:208
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff814afc00-ffffffff814afd52: aa_label_sk_perm.part.0 (STB_LOCAL)
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
In security/apparmor/net.c (ffffffff8150f4c5)
Location: security/apparmor/net.c:209
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff8150f070-ffffffff8150f1c2: aa_label_sk_perm.part.0 (STB_LOCAL)
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
In security/apparmor/net.c (ffffffff8152c305)
Location: security/apparmor/net.c:211
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff8152beb0-ffffffff8152c002: aa_label_sk_perm.part.0 (STB_LOCAL)
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
In security/apparmor/net.c (ffffffff815325a5)
Location: security/apparmor/net.c:211
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff81532150-ffffffff815322a2: aa_label_sk_perm.part.0 (STB_LOCAL)
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
In security/apparmor/net.c (ffffffff81590b25)
Location: security/apparmor/net.c:211
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff815906d0-ffffffff81590822: aa_label_sk_perm.part.0 (STB_LOCAL)
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
In security/apparmor/net.c (ffffffff81631c95)
Location: security/apparmor/net.c:211
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff816317a0-ffffffff81631910: aa_label_sk_perm.part.0 (STB_LOCAL)
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
In security/apparmor/net.c (ffffffff816e6a25)
Location: security/apparmor/net.c:213
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff816e64f0-ffffffff816e6651: aa_label_sk_perm.part.0 (STB_LOCAL)
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
In security/apparmor/net.c (ffffffff81720185)
Location: security/apparmor/net.c:213
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff8171fc20-ffffffff8171fd81: aa_label_sk_perm.part.0 (STB_LOCAL)
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
In security/apparmor/net.c (ffffffff8175ebd8)
Location: security/apparmor/net.c:216
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff8175e650-ffffffff8175e7b1: aa_label_sk_perm.part.0 (STB_LOCAL)
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
In security/apparmor/net.c (ffff8000105a77a8)
Location: security/apparmor/net.c:208
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffff8000105a7378-ffff8000105a74b4: aa_label_sk_perm.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/net.c (c0757750)
Location: security/apparmor/net.c:208
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
c075732c-c0757480: aa_label_sk_perm.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/net.c (c000000000724200)
Location: security/apparmor/net.c:208
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
c000000000723c60-c000000000723e04: aa_label_sk_perm.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/net.c (ffffffe0003f0f3e)
Location: security/apparmor/net.c:208
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffe0003f0be8-ffffffe0003f0cfa: aa_label_sk_perm.part.0 (STB_LOCAL)
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
In security/apparmor/net.c (ffffffff814a85f5)
Location: security/apparmor/net.c:208
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff814a81e0-ffffffff814a8332: aa_label_sk_perm.part.0 (STB_LOCAL)
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
In security/apparmor/net.c (ffffffff81499015)
Location: security/apparmor/net.c:208
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff81498c00-ffffffff81498d52: aa_label_sk_perm.part.0 (STB_LOCAL)
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
In security/apparmor/net.c (ffffffff814a4695)
Location: security/apparmor/net.c:208
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff814a4280-ffffffff814a43d2: aa_label_sk_perm.part.0 (STB_LOCAL)
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
In security/apparmor/net.c (ffffffff814bcf25)
Location: security/apparmor/net.c:208
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
Direct callers:
  - security/apparmor/net.c:aa_sock_file_perm
  - security/apparmor/net.c:aa_sk_perm
```
**Symbols:**

```
ffffffff814bcb10-ffffffff814bcc62: aa_label_sk_perm.part.0 (STB_LOCAL)
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
</ul>
