# validation

# 5.29
## V1
- field validation 
- global validation
- template validation
- Safe Navigation Operator
## V2
- spring bindingResult(To replace v1 errors code)
  - field error
  - object error
### thymeleaf
  - #fields
  - th:errors
  - th:errorclass

# 5.30
## v2
- spring bindingResult
- field error(save input values error when an error accurs)
  - rejected value(save input values error when an error accurs)
  - Binding Failure(Binding failure recognition such as type error, validation error recognition distinguished value)
- create message code and using
  - create error.properties and using 
  - be capable of internationalization(ex) error_en.properties)
  - delete defaultMessage

# 5.31
## v2
- using reject, rejectedValue()
- MessageCodesResolver
  - Automatic generation of error codes
    - FieldError, ObjectError
- using Validator

# 6.3
# 6.4
- validator
  - @NotNull, @NotBlank, @Max, @Range
- ValidatorFactory
- Violation
  - violation.getMessage




