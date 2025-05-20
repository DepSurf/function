# Function: <code>ima_log_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ima_log_string(struct audit_buffer *ab, char *key, char *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81398d80)
Location: security/integrity/ima/ima_policy.c:492
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff81398d80-ffffffff81398dc0: ima_log_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ima_log_string(struct audit_buffer *ab, char *key, char *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff813d5340)
Location: security/integrity/ima/ima_policy.c:544
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff813d5340-ffffffff813d5380: ima_log_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ima_log_string(struct audit_buffer *ab, char *key, char *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff813ecda0)
Location: security/integrity/ima/ima_policy.c:544
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff813ecda0-ffffffff813ecde0: ima_log_string (STB_LOCAL)
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
In security/integrity/ima/ima_policy.c (ffffffff813f94b3)
Location: security/integrity/ima/ima_policy.c:603
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff8142193c)
Location: security/integrity/ima/ima_policy.c:603
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff81453f2c)
Location: security/integrity/ima/ima_policy.c:627
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff81470f7c)
Location: security/integrity/ima/ima_policy.c:756
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff8149e9be)
Location: security/integrity/ima/ima_policy.c:841
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff814b8e58)
Location: security/integrity/ima/ima_policy.c:855
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8151901f)
Location: security/integrity/ima/ima_policy.c:969
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff815360bf)
Location: security/integrity/ima/ima_policy.c:1014
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8153e7e0)
Location: security/integrity/ima/ima_policy.c:1055
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8159dbd0)
Location: security/integrity/ima/ima_policy.c:1111
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81643115)
Location: security/integrity/ima/ima_policy.c:1174
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff816fb3d5)
Location: security/integrity/ima/ima_policy.c:1221
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff817354e3)
Location: security/integrity/ima/ima_policy.c:1223
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81775fc3)
Location: security/integrity/ima/ima_policy.c:1216
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffff8000105b140c)
Location: security/integrity/ima/ima_policy.c:855
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (c0760ad4)
Location: security/integrity/ima/ima_policy.c:855
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (c0000000007315b0)
Location: security/integrity/ima/ima_policy.c:855
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffe0003f8e10)
Location: security/integrity/ima/ima_policy.c:855
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff814b1438)
Location: security/integrity/ima/ima_policy.c:855
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff814a1e58)
Location: security/integrity/ima/ima_policy.c:855
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff814ad4c8)
Location: security/integrity/ima/ima_policy.c:855
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
In security/integrity/ima/ima_policy.c (ffffffff814c5f18)
Location: security/integrity/ima/ima_policy.c:855
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
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
</ul>
