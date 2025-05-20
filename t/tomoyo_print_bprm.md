# Function: <code>tomoyo_print_bprm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff81366ef3)
Location: security/tomoyo/audit.c:21
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8139cf8e)
Location: security/tomoyo/audit.c:21
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff813b3b6e)
Location: security/tomoyo/audit.c:21
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff813ca5bb)
Location: security/tomoyo/audit.c:21
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff813f0a5b)
Location: security/tomoyo/audit.c:22
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff81421987)
Location: security/tomoyo/audit.c:22
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8143dffc)
Location: security/tomoyo/audit.c:22
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8146be38)
Location: security/tomoyo/audit.c:22
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff81485c18)
Location: security/tomoyo/audit.c:22
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *tomoyo_print_bprm(struct linux_binprm *bprm, struct tomoyo_page_dump *dump);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff814dbd20)
Location: security/tomoyo/audit.c:22
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff814dbd20-ffffffff814dbff7: tomoyo_print_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *tomoyo_print_bprm(struct linux_binprm *bprm, struct tomoyo_page_dump *dump);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff814f9170)
Location: security/tomoyo/audit.c:22
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff814f9170-ffffffff814f9447: tomoyo_print_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *tomoyo_print_bprm(struct linux_binprm *bprm, struct tomoyo_page_dump *dump);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff814ffec0)
Location: security/tomoyo/audit.c:22
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff814ffec0-ffffffff81500197: tomoyo_print_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *tomoyo_print_bprm(struct linux_binprm *bprm, struct tomoyo_page_dump *dump);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8155b000)
Location: security/tomoyo/audit.c:22
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff8155b000-ffffffff8155b2d7: tomoyo_print_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *tomoyo_print_bprm(struct linux_binprm *bprm, struct tomoyo_page_dump *dump);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff815f5e10)
Location: security/tomoyo/audit.c:22
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff815f5e10-ffffffff815f6102: tomoyo_print_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *tomoyo_print_bprm(struct linux_binprm *bprm, struct tomoyo_page_dump *dump);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff816a6920)
Location: security/tomoyo/audit.c:22
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff816a6920-ffffffff816a6c02: tomoyo_print_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *tomoyo_print_bprm(struct linux_binprm *bprm, struct tomoyo_page_dump *dump);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff816df270)
Location: security/tomoyo/audit.c:22
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff816df270-ffffffff816df66e: tomoyo_print_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *tomoyo_print_bprm(struct linux_binprm *bprm, struct tomoyo_page_dump *dump);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8171be90)
Location: security/tomoyo/audit.c:22
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff8171be90-ffffffff8171c2bd: tomoyo_print_bprm (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffff80001057805c)
Location: security/tomoyo/audit.c:22
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (c072afa4)
Location: security/tomoyo/audit.c:22
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
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
In security/tomoyo/audit.c (c0000000006e1a0c)
Location: security/tomoyo/audit.c:22
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
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
In security/tomoyo/audit.c (ffffffe0003ca4da)
Location: security/tomoyo/audit.c:22
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8147e1f8)
Location: security/tomoyo/audit.c:22
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8146ec18)
Location: security/tomoyo/audit.c:22
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8147a298)
Location: security/tomoyo/audit.c:22
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff81491d58)
Location: security/tomoyo/audit.c:22
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
