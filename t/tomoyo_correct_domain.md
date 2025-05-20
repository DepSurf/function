# Function: <code>tomoyo_correct_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81374400)
Location: security/tomoyo/util.c:545
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff81374400-ffffffff813744a7: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813aa800)
Location: security/tomoyo/util.c:545
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff813aa800-ffffffff813aa8a3: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813c1380)
Location: security/tomoyo/util.c:545
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff813c1380-ffffffff813c1423: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813d7d00)
Location: security/tomoyo/util.c:547
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff813d7d00-ffffffff813d7d99: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813fe150)
Location: security/tomoyo/util.c:527
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff813fe150-ffffffff813fe1e9: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8142f050)
Location: security/tomoyo/util.c:527
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff8142f050-ffffffff8142f0e9: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8144ba70)
Location: security/tomoyo/util.c:527
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff8144ba70-ffffffff8144bb0a: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff814797c0)
Location: security/tomoyo/util.c:536
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff814797c0-ffffffff81479858: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff814934c0)
Location: security/tomoyo/util.c:536
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff814934c0-ffffffff81493558: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff814ea880)
Location: security/tomoyo/util.c:536
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_update_manager_entry
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff814ea880-ffffffff814ea91e: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81507c70)
Location: security/tomoyo/util.c:559
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_update_manager_entry
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff81507c70-ffffffff81507d02: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8150e7f0)
Location: security/tomoyo/util.c:559
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff8150e7f0-ffffffff8150e882: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8156c340)
Location: security/tomoyo/util.c:559
Inline: True
Direct callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff8156c340-ffffffff8156c3d2: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff816086e0)
Location: security/tomoyo/util.c:559
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff816086e0-ffffffff81608768: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff816b9f60)
Location: security/tomoyo/util.c:559
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff816b9f60-ffffffff816b9fe8: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff816f2900)
Location: security/tomoyo/util.c:559
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff816f2900-ffffffff816f2988: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8172f6c0)
Location: security/tomoyo/util.c:559
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff8172f6c0-ffffffff8172f748: tomoyo_correct_domain (STB_GLOBAL)
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
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffff800010588750)
Location: security/tomoyo/util.c:536
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffff800010588750-ffff80001058880c: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (c0739bd0)
Location: security/tomoyo/util.c:536
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
c0739bd0-c0739c84: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (c0000000006f8dd0)
Location: security/tomoyo/util.c:536
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
c0000000006f8dd0-c0000000006f8ed4: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffe0003d77a8)
Location: security/tomoyo/util.c:536
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffe0003d77a8-ffffffe0003d785c: tomoyo_correct_domain (STB_GLOBAL)
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
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8148baa0)
Location: security/tomoyo/util.c:536
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff8148baa0-ffffffff8148bb38: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8147c4c0)
Location: security/tomoyo/util.c:536
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff8147c4c0-ffffffff8147c558: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81487b40)
Location: security/tomoyo/util.c:536
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff81487b40-ffffffff81487bd8: tomoyo_correct_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool tomoyo_correct_domain(const unsigned char *domainname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8149f680)
Location: security/tomoyo/util.c:536
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff8149f680-ffffffff8149f718: tomoyo_correct_domain (STB_GLOBAL)
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
