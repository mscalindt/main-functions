A collection of reusable pure POSIX `sh` functions to make shell option parsing
a breeze.

## Functions List:

- [ASSERT()](https://github.com/mscalindt/main-functions/blob/main/src/assert)
- [COPT()](https://github.com/mscalindt/main-functions/blob/main/src/copt)
- [COPT_OPTIONAL()](https://github.com/mscalindt/main-functions/blob/main/src/copt_optional)
- [FPATH()](https://github.com/mscalindt/main-functions/blob/main/src/fpath)
- [OPD_CMAX()](https://github.com/mscalindt/main-functions/blob/main/src/opd_cmax)
- [OPD_MAX()](https://github.com/mscalindt/main-functions/blob/main/src/opd_max)
- [OPD_MIN()](https://github.com/mscalindt/main-functions/blob/main/src/opd_min)
- [OPT_ERR()](https://github.com/mscalindt/main-functions/blob/main/src/opt_err)
- [OPT_FAIL()](https://github.com/mscalindt/main-functions/blob/main/src/opt_fail)
- [OPT_INVALID()](https://github.com/mscalindt/main-functions/blob/main/src/opt_invalid)
- [OPT_UNKNOWN()](https://github.com/mscalindt/main-functions/blob/main/src/opt_unknown)
- [OPT_UNRECOGNIZED()](https://github.com/mscalindt/main-functions/blob/main/src/opt_unrecognized)
- [SCOPT()](https://github.com/mscalindt/main-functions/blob/main/src/scopt)
- [SCOPT_OPTIONAL()](https://github.com/mscalindt/main-functions/blob/main/src/scopt_optional)
- [SOPT()](https://github.com/mscalindt/main-functions/blob/main/src/sopt)
- [SSOPT()](https://github.com/mscalindt/main-functions/blob/main/src/ssopt)

## Brief Descriptions:

### [ASSERT()](https://github.com/mscalindt/main-functions/blob/main/src/assert)
Assert a string

### [COPT()](https://github.com/mscalindt/main-functions/blob/main/src/copt)
True if complex (argument) option

### [COPT_OPTIONAL()](https://github.com/mscalindt/main-functions/blob/main/src/copt_optional)
True if optional-complex (possible argument) option

### [FPATH()](https://github.com/mscalindt/main-functions/blob/main/src/fpath)
Convert relative path and/or store the full path in $_fpath

### [OPD_CMAX()](https://github.com/mscalindt/main-functions/blob/main/src/opd_cmax)
Signify invalid operand count (max)[X>X]

### [OPD_MAX()](https://github.com/mscalindt/main-functions/blob/main/src/opd_max)
Signify invalid operand count (max)[X>1]

### [OPD_MIN()](https://github.com/mscalindt/main-functions/blob/main/src/opd_min)
Signify invalid operand count (min)[0>X]

### [OPT_ERR()](https://github.com/mscalindt/main-functions/blob/main/src/opt_err)
Signify invalid option argument

### [OPT_FAIL()](https://github.com/mscalindt/main-functions/blob/main/src/opt_fail)
opt_err() wrapper

### [OPT_INVALID()](https://github.com/mscalindt/main-functions/blob/main/src/opt_invalid)
Signify invalid option

### [OPT_UNKNOWN()](https://github.com/mscalindt/main-functions/blob/main/src/opt_unknown)
Signify unknown (*) option

### [OPT_UNRECOGNIZED()](https://github.com/mscalindt/main-functions/blob/main/src/opt_unrecognized)
Signify unrecognized ('--') option

### [SCOPT()](https://github.com/mscalindt/main-functions/blob/main/src/scopt)
True if specific complex (argument) option

### [SCOPT_OPTIONAL()](https://github.com/mscalindt/main-functions/blob/main/src/scopt_optional)
True if specific optional-complex (possible argument) option

### [SOPT()](https://github.com/mscalindt/main-functions/blob/main/src/sopt)
True if simple (no argument) option

### [SSOPT()](https://github.com/mscalindt/main-functions/blob/main/src/ssopt)
True if specific simple (no argument) option