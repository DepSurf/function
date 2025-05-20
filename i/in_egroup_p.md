# Function: <code>in_egroup_p</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810a4210)
Location: kernel/groups.c:267
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - fs/quota/quota.c:SyS_quotactl
  - fs/proc/proc_sysctl.c:test_perm
  - security/apparmor/policy.c:aa_may_open_profiles
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff810a4210-ffffffff810a4282: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810a7950)
Location: kernel/groups.c:267
Inline: False
Direct callers:
  - fs/quota/quota.c:SyS_quotactl
  - fs/proc/proc_sysctl.c:test_perm
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff810a7950-ffffffff810a79c2: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810adad0)
Location: kernel/groups.c:242
Inline: False
Direct callers:
  - fs/quota/quota.c:SyS_quotactl
  - fs/proc/proc_sysctl.c:test_perm
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff810adad0-ffffffff810adb2e: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810aa6a0)
Location: kernel/groups.c:229
Inline: False
Direct callers:
  - fs/quota/quota.c:SyS_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff810aa6a0-ffffffff810aa705: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b1360)
Location: kernel/groups.c:231
Inline: False
Direct callers:
  - fs/quota/quota.c:SyS_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff810b1360-ffffffff810b13c5: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b8160)
Location: kernel/groups.c:231
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
```
**Symbols:**

```
ffffffff810b8160-ffffffff810b81c3: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c1240)
Location: kernel/groups.c:231
Inline: False
Direct callers:
  - fs/quota/quota.c:kernel_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
```
**Symbols:**

```
ffffffff810c1240-ffffffff810c12a3: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c7330)
Location: kernel/groups.c:231
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
```
**Symbols:**

```
ffffffff810c7330-ffffffff810c739c: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d0400)
Location: kernel/groups.c:231
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
```
**Symbols:**

```
ffffffff810d0400-ffffffff810d046c: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810da5e0)
Location: kernel/groups.c:231
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
```
**Symbols:**

```
ffffffff810da5e0-ffffffff810da651: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d5d40)
Location: kernel/groups.c:231
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
```
**Symbols:**

```
ffffffff810d5d40-ffffffff810d5db1: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d7a00)
Location: kernel/groups.c:226
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
```
**Symbols:**

```
ffffffff810d7a00-ffffffff810d7a71: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810eb2b0)
Location: kernel/groups.c:226
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
```
**Symbols:**

```
ffffffff810eb2b0-ffffffff810eb321: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff811061b0)
Location: kernel/groups.c:226
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:aa_policy_view_capable
```
**Symbols:**

```
ffffffff811061b0-ffffffff8110624c: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff8112bdf0)
Location: kernel/groups.c:239
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:aa_policy_view_capable
```
**Symbols:**

```
ffffffff8112bdf0-ffffffff8112be8c: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81138c50)
Location: kernel/groups.c:239
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:aa_policy_view_capable
```
**Symbols:**

```
ffffffff81138c50-ffffffff81138cec: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81143990)
Location: kernel/groups.c:239
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:aa_policy_view_capable
```
**Symbols:**

```
ffffffff81143990-ffffffff81143a2c: in_egroup_p (STB_GLOBAL)
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
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffff800010130ab8)
Location: kernel/groups.c:231
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
```
**Symbols:**

```
ffff800010130ab8-ffff800010130b4c: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (c038030c)
Location: kernel/groups.c:231
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
```
**Symbols:**

```
c038030c-c0380398: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (c00000000017a1c0)
Location: kernel/groups.c:231
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
```
**Symbols:**

```
c00000000017a1c0-c00000000017a258: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffe0000e3e4e)
Location: kernel/groups.c:231
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
```
**Symbols:**

```
ffffffe0000e3e4e-ffffffe0000e3eca: in_egroup_p (STB_GLOBAL)
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
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810ca780)
Location: kernel/groups.c:231
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
```
**Symbols:**

```
ffffffff810ca780-ffffffff810ca7ec: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b8f90)
Location: kernel/groups.c:231
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
```
**Symbols:**

```
ffffffff810b8f90-ffffffff810b8ffc: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c9cb0)
Location: kernel/groups.c:231
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
```
**Symbols:**

```
ffffffff810c9cb0-ffffffff810c9d1c: in_egroup_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int in_egroup_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d2200)
Location: kernel/groups.c:231
Inline: False
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/proc/proc_sysctl.c:sysctl_perm
  - security/apparmor/policy.c:policy_view_capable
```
**Symbols:**

```
ffffffff810d2200-ffffffff810d226c: in_egroup_p (STB_GLOBAL)
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
