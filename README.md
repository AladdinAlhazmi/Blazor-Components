# Blazor-Components


//Call ModalDialog 
```cs
    <ModalDialog Title='AreYouSure'
             Text='ConfirmDelete"'
             OnClose="@OnDialogClose"
             DialogType="ModalDialogType.DeleteCancel">
    </ModalDialog>
```
        
//Call ToastDialog 
```cs
   <ToastDialog IsSuccessed='true'
          ToastMessage='toastMessage'>
   </ToastDialog>
```
