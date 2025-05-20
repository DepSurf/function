# Function: <code>shutdown_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char **vec, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/manage.c (ffffffff814c7140)
Location: drivers/xen/manage.c:209
Inline: False
```
**Symbols:**

```
ffffffff814c7140-ffffffff814c729c: shutdown_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char **vec, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/manage.c (ffffffff815179c0)
Location: drivers/xen/manage.c:209
Inline: False
```
**Symbols:**

```
ffffffff815179c0-ffffffff81517b19: shutdown_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char **vec, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/manage.c (ffffffff81544290)
Location: drivers/xen/manage.c:220
Inline: False
```
**Symbols:**

```
ffffffff81544290-ffffffff815443dc: shutdown_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/manage.c (ffffffff81558120)
Location: drivers/xen/manage.c:221
Inline: False
```
**Symbols:**

```
ffffffff81558120-ffffffff8155826c: shutdown_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/manage.c (ffffffff815bc2a0)
Location: drivers/xen/manage.c:218
Inline: False
```
**Symbols:**

```
ffffffff815bc2a0-ffffffff815bc3f2: shutdown_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:218
Inline: False
```
**Symbols:**

```
ffffffff815f4770-ffffffff815f48b5: shutdown_handler (STB_LOCAL)
ffffffff815f4a8a-ffffffff815f4aa8: shutdown_handler.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:218
Inline: False
```
**Symbols:**

```
ffffffff8160f5d0-ffffffff8160f715: shutdown_handler (STB_LOCAL)
ffffffff8160f8ea-ffffffff8160f908: shutdown_handler.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:219
Inline: False
```
**Symbols:**

```
ffffffff816433d0-ffffffff81643511: shutdown_handler (STB_LOCAL)
ffffffff816436f7-ffffffff81643715: shutdown_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:219
Inline: False
```
**Symbols:**

```
ffffffff81665970-ffffffff81665ab1: shutdown_handler (STB_LOCAL)
ffffffff81665c97-ffffffff81665cb5: shutdown_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:219
Inline: False
```
**Symbols:**

```
ffffffff81715030-ffffffff81715171: shutdown_handler (STB_LOCAL)
ffffffff817153f8-ffffffff81715416: shutdown_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:220
Inline: False
```
**Symbols:**

```
ffffffff81731c20-ffffffff81731d61: shutdown_handler (STB_LOCAL)
ffffffff81c04e7e-ffffffff81c04e9c: shutdown_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:220
Inline: False
```
**Symbols:**

```
ffffffff81715710-ffffffff81715851: shutdown_handler (STB_LOCAL)
ffffffff81bf6b08-ffffffff81bf6b26: shutdown_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:220
Inline: False
```
**Symbols:**

```
ffffffff81792720-ffffffff81792896: shutdown_handler (STB_LOCAL)
ffffffff81cf5742-ffffffff81cf5760: shutdown_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:220
Inline: False
```
**Symbols:**

```
ffffffff818caf30-ffffffff818cb0b5: shutdown_handler (STB_LOCAL)
ffffffff81ebd84d-ffffffff81ebd86b: shutdown_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/manage.c (ffffffff81a1c170)
Location: drivers/xen/manage.c:220
Inline: False
```
**Symbols:**

```
ffffffff81a1c170-ffffffff81a1c30c: shutdown_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/manage.c (ffffffff81a65310)
Location: drivers/xen/manage.c:220
Inline: False
```
**Symbols:**

```
ffffffff81a65310-ffffffff81a654ac: shutdown_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/manage.c (ffffffff81ab7b70)
Location: drivers/xen/manage.c:220
Inline: False
```
**Symbols:**

```
ffffffff81ab7b70-ffffffff81ab7d0c: shutdown_handler (STB_LOCAL)
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
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/manage.c (ffff80001082f558)
Location: drivers/xen/manage.c:219
Inline: False
```
**Symbols:**

```
ffff80001082f558-ffff80001082f710: shutdown_handler (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:253
Inline: False
```
**Symbols:**

```
ffffffff8162b510-ffffffff8162b651: shutdown_handler (STB_LOCAL)
ffffffff8162b8f0-ffffffff8162b90e: shutdown_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:219
Inline: False
```
**Symbols:**

```
ffffffff816597b0-ffffffff816598f1: shutdown_handler (STB_LOCAL)
ffffffff81659ad7-ffffffff81659af5: shutdown_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void shutdown_handler(struct xenbus_watch *watch, const char *path, const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/manage.c (0)
Location: drivers/xen/manage.c:219
Inline: False
```
**Symbols:**

```
ffffffff81673db0-ffffffff81673ef1: shutdown_handler (STB_LOCAL)
ffffffff816740d7-ffffffff816740f5: shutdown_handler.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *path</code>
</li>
<li>
<b>Param added. </b>
<code>const char *token</code>
</li>
<li>
<b>Param removed. </b>
<code>const char **vec</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int len</code>
</li>
</ul>
</details>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
