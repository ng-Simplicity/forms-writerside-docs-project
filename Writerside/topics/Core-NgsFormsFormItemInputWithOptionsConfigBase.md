# NgsFormsFormItemConfigBaseInputWithOptions

## Description


## Detail
* Path: `libs/forms-core/src/models/item-config-bases/form-item-text-input-config-base.model.ts`

## Source
```typescript
export interface NgsFormsFormItemConfigBaseInputWithOptions
  extends NgsFormsFormItemConfigBaseTextInput {
  options?: Array<NgsFormsFormInputOption>;
  options$?: Observable<Array<NgsFormsFormInputOption>>;
}
```
