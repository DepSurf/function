# Function: <code>hashtab_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8134e650)
Location: security/selinux/ss/hashtab.c:120
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
```
**Symbols:**

```
ffffffff8134e650-ffffffff8134e6c1: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81384640)
Location: security/selinux/ss/hashtab.c:120
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
ffffffff81384640-ffffffff813846ba: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8139b0d0)
Location: security/selinux/ss/hashtab.c:120
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
ffffffff8139b0d0-ffffffff8139b14a: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff813b17f0)
Location: security/selinux/ss/hashtab.c:120
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
ffffffff813b17f0-ffffffff813b186a: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff813d78e0)
Location: security/selinux/ss/hashtab.c:123
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
ffffffff813d78e0-ffffffff813d795c: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81407f50)
Location: security/selinux/ss/hashtab.c:123
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
ffffffff81407f50-ffffffff81407fcc: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81423ab0)
Location: security/selinux/ss/hashtab.c:123
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
ffffffff81423ab0-ffffffff81423b2c: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81451610)
Location: security/selinux/ss/hashtab.c:123
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
ffffffff81451610-ffffffff8145168c: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8146b3f0)
Location: security/selinux/ss/hashtab.c:123
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
ffffffff8146b3f0-ffffffff8146b46c: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814bf950)
Location: security/selinux/ss/hashtab.c:125
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
ffffffff814bf950-ffffffff814bf9c7: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814dd110)
Location: security/selinux/ss/hashtab.c:78
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_policydb_destroy_dup
```
**Symbols:**

```
ffffffff814dd110-ffffffff814dd187: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814e3a80)
Location: security/selinux/ss/hashtab.c:78
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_policydb_destroy_dup
```
**Symbols:**

```
ffffffff814e3a80-ffffffff814e3af7: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8153cea0)
Location: security/selinux/ss/hashtab.c:85
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff8153cea0-ffffffff8153cf17: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff815d48c0)
Location: security/selinux/ss/hashtab.c:86
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff815d48c0-ffffffff815d4956: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81682a10)
Location: security/selinux/ss/hashtab.c:86
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff81682a10-ffffffff81682aa6: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff816bab90)
Location: security/selinux/ss/hashtab.c:86
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff816bab90-ffffffff816bac23: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff816f7620)
Location: security/selinux/ss/hashtab.c:86
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_policydb_dup
```
**Symbols:**

```
ffffffff816f7620-ffffffff816f76b3: hashtab_map (STB_GLOBAL)
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
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffff80001055a178)
Location: security/selinux/ss/hashtab.c:123
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
ffff80001055a178-ffff80001055a214: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (c070ea08)
Location: security/selinux/ss/hashtab.c:123
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
c070ea08-c070ea84: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (c0000000006b8690)
Location: security/selinux/ss/hashtab.c:123
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
c0000000006b8690-c0000000006b879c: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffe0003b1238)
Location: security/selinux/ss/hashtab.c:123
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
ffffffe0003b1238-ffffffe0003b12ae: hashtab_map (STB_GLOBAL)
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
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff814639d0)
Location: security/selinux/ss/hashtab.c:123
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
ffffffff814639d0-ffffffff81463a4c: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81454400)
Location: security/selinux/ss/hashtab.c:123
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
ffffffff81454400-ffffffff8145447c: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff8145fa70)
Location: security/selinux/ss/hashtab.c:123
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
ffffffff8145fa70-ffffffff8145faec: hashtab_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hashtab_map(struct hashtab *h, int (*apply)(void *, void *, void *), void *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/hashtab.c (ffffffff81477280)
Location: security/selinux/ss/hashtab.c:123
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:policydb_write
  - security/selinux/ss/policydb.c:class_write
  - security/selinux/ss/policydb.c:common_write
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_index
  - security/selinux/ss/policydb.c:cls_destroy
  - security/selinux/ss/policydb.c:common_destroy
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
```
**Symbols:**

```
ffffffff81477280-ffffffff814772fc: hashtab_map (STB_GLOBAL)
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
