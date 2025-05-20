# Function: <code>security_sb_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133d1c0)
Location: security/security.c:274
Inline: False
Direct callers:
  - fs/super.c:destroy_super
```
**Symbols:**

```
ffffffff8133d1c0-ffffffff8133d1f6: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813727f0)
Location: security/security.c:275
Inline: False
Direct callers:
  - fs/super.c:destroy_super
```
**Symbols:**

```
ffffffff813727f0-ffffffff81372826: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81389120)
Location: security/security.c:275
Inline: False
Direct callers:
  - fs/super.c:destroy_super
```
**Symbols:**

```
ffffffff81389120-ffffffff81389156: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139e4b0)
Location: security/security.c:850
Inline: False
Direct callers:
  - fs/super.c:destroy_super
```
**Symbols:**

```
ffffffff8139e4b0-ffffffff8139e4ff: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c3db0)
Location: security/security.c:798
Inline: False
Direct callers:
  - security/security.c:security_sb_alloc
```
**Symbols:**

```
ffffffff813c3db0-ffffffff813c3e05: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f4430)
Location: security/security.c:368
Inline: False
```
**Symbols:**

```
ffffffff813f4430-ffffffff813f4464: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140f810)
Location: security/security.c:850
Inline: False
```
**Symbols:**

```
ffffffff8140f810-ffffffff8140f844: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143cda0)
Location: security/security.c:859
Inline: False
```
**Symbols:**

```
ffffffff8143cda0-ffffffff8143cdd6: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81456870)
Location: security/security.c:893
Inline: False
```
**Symbols:**

```
ffffffff81456870-ffffffff814568a4: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a9680)
Location: security/security.c:1041
Inline: False
```
**Symbols:**

```
ffffffff814a9680-ffffffff814a96b4: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c6c80)
Location: security/security.c:1043
Inline: False
```
**Symbols:**

```
ffffffff814c6c80-ffffffff814c6cb4: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ccda5)
Location: security/security.c:1079
Inline: True
Inline callers:
  - security/security.c:security_sb_alloc
```
**Symbols:**

```
ffffffff814cce30-ffffffff814cce7d: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81525f25)
Location: security/security.c:1079
Inline: True
Inline callers:
  - security/security.c:security_sb_alloc
```
**Symbols:**

```
ffffffff81525fb0-ffffffff81525ffd: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815ba286)
Location: security/security.c:1091
Inline: True
Inline callers:
  - security/security.c:security_sb_alloc
```
**Symbols:**

```
ffffffff815ba350-ffffffff815ba3a5: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81665b96)
Location: security/security.c:1089
Inline: True
Inline callers:
  - security/security.c:security_sb_alloc
```
**Symbols:**

```
ffffffff81665c80-ffffffff81665cd5: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169e186)
Location: security/security.c:1378
Inline: True
Inline callers:
  - security/security.c:security_sb_alloc
```
**Symbols:**

```
ffffffff8169e270-ffffffff8169e2c5: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816daa96)
Location: security/security.c:1418
Inline: True
Inline callers:
  - security/security.c:security_sb_alloc
Direct callers:
  - fs/super.c:destroy_super_work
```
**Symbols:**

```
ffffffff816dab80-ffffffff816dabd5: security_sb_free (STB_GLOBAL)
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
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105421b8)
Location: security/security.c:893
Inline: False
```
**Symbols:**

```
ffff8000105421b8-ffff800010542200: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f816c)
Location: security/security.c:893
Inline: False
```
**Symbols:**

```
c06f816c-c06f81b4: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006951e0)
Location: security/security.c:893
Inline: False
```
**Symbols:**

```
c0000000006951e0-c000000000695258: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039ebc6)
Location: security/security.c:893
Inline: False
```
**Symbols:**

```
ffffffe00039ebc6-ffffffe00039ebfe: security_sb_free (STB_GLOBAL)
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
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144ee50)
Location: security/security.c:893
Inline: False
```
**Symbols:**

```
ffffffff8144ee50-ffffffff8144ee84: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143f8a0)
Location: security/security.c:893
Inline: False
```
**Symbols:**

```
ffffffff8143f8a0-ffffffff8143f8d4: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144aef0)
Location: security/security.c:893
Inline: False
```
**Symbols:**

```
ffffffff8144aef0-ffffffff8144af24: security_sb_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_sb_free(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814622c0)
Location: security/security.c:893
Inline: False
```
**Symbols:**

```
ffffffff814622c0-ffffffff814622f4: security_sb_free (STB_GLOBAL)
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
