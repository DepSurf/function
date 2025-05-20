# Function: <code>mls_context_cpy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8134e996)
Location: security/selinux/ss/context.h:40
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_insert
```
```
In security/selinux/ss/services.c (ffffffff81356a90)
Location: security/selinux/ss/context.h:40
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff8135bfb4)
Location: security/selinux/ss/context.h:40
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81384986)
Location: security/selinux/ss/context.h:40
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_insert
```
```
In security/selinux/ss/services.c (ffffffff8138faf0)
Location: security/selinux/ss/context.h:40
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff813927a8)
Location: security/selinux/ss/context.h:40
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8139b416)
Location: security/selinux/ss/context.h:40
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_insert
```
```
In security/selinux/ss/services.c (ffffffff813a6710)
Location: security/selinux/ss/context.h:40
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff813a93d8)
Location: security/selinux/ss/context.h:40
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int mls_context_cpy(struct context *dst, struct context *src);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff813b1b3e)
Location: security/selinux/ss/context.h:40
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_insert
```
```
In security/selinux/ss/services.c (ffffffff813bd15e)
Location: security/selinux/ss/context.h:40
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff813bfe6f)
Location: security/selinux/ss/context.h:40
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
Direct callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff813beda0-ffffffff813bee0b: mls_context_cpy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int mls_context_cpy(struct context *dst, struct context *src);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff813d7c7e)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_insert
```
```
In security/selinux/ss/services.c (ffffffff813e32ce)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff813e600f)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
Direct callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
**Symbols:**

```
ffffffff813e4f40-ffffffff813e4fab: mls_context_cpy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814082ad)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_insert
```
```
In security/selinux/ss/services.c (ffffffff81413a96)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff81416bc4)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814248b9)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffffffff8142ffdc)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff814330b4)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8145244f)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffffffff8145d964)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff81460a93)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8146c1fa)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffffffff81477714)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff8147a843)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814c0768)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffffffff814ccb6a)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff814cfe26)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814de1e8)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffffffff814ea39f)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff814ed350)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814e4b5f)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffffffff814f0f36)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff814f40ee)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8153e1ab)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffffffff8154b522)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff8154ea9e)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff815d5bbc)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffffffff815e431e)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff815e7bea)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81683e16)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffffffff81693633)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff816972da)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff816bc176)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffffffff816cbb40)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff816cf85b)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff816f8ca6)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffffffff81708800)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff8170be7b)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_context_to_sid
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffff80001055b0bc)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffff800010567468)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffff80001056ae40)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (c070f8f8)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (c071b960)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (c071e9ac)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (c0000000006ba2f4)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (c0000000006ca82c)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (c0000000006ceb6c)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffe0003b1f08)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffffffe0003bd13a)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffe0003bfc04)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814647da)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffffffff8146fcf4)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff81472e23)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8145520a)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffffffff81460714)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff81463843)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8146087a)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffffffff8146bd94)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff8146eec3)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8147807a)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
```
In security/selinux/ss/services.c (ffffffff81483544)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
```
```
In security/selinux/ss/mls.c (ffffffff81486733)
Location: security/selinux/ss/context.h:41
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
  - security/selinux/ss/mls.c:mls_compute_sid
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
