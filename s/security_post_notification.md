# Function: <code>security_post_notification</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_post_notification(const struct cred *w_cred, const struct cred *cred, struct watch_notification *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814abd10)
Location: security/security.c:2445
Inline: False
```
**Symbols:**

```
ffffffff814abd10-ffffffff814abd5e: security_post_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_post_notification(const struct cred *w_cred, const struct cred *cred, struct watch_notification *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c9310)
Location: security/security.c:2462
Inline: False
```
**Symbols:**

```
ffffffff814c9310-ffffffff814c935e: security_post_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_post_notification(const struct cred *w_cred, const struct cred *cred, struct watch_notification *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cf940)
Location: security/security.c:2525
Inline: False
```
**Symbols:**

```
ffffffff814cf940-ffffffff814cf98e: security_post_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_post_notification(const struct cred *w_cred, const struct cred *cred, struct watch_notification *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81528670)
Location: security/security.c:2533
Inline: False
```
**Symbols:**

```
ffffffff81528670-ffffffff815286be: security_post_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_post_notification(const struct cred *w_cred, const struct cred *cred, struct watch_notification *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bd830)
Location: security/security.c:2563
Inline: False
```
**Symbols:**

```
ffffffff815bd830-ffffffff815bd89d: security_post_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_post_notification(const struct cred *w_cred, const struct cred *cred, struct watch_notification *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81669850)
Location: security/security.c:2543
Inline: False
```
**Symbols:**

```
ffffffff81669850-ffffffff816698bd: security_post_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_post_notification(const struct cred *w_cred, const struct cred *cred, struct watch_notification *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a1e30)
Location: security/security.c:4283
Inline: False
```
**Symbols:**

```
ffffffff816a1e30-ffffffff816a1e9d: security_post_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_post_notification(const struct cred *w_cred, const struct cred *cred, struct watch_notification *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816de9a0)
Location: security/security.c:4444
Inline: False
```
**Symbols:**

```
ffffffff816de9a0-ffffffff816dea0d: security_post_notification (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
