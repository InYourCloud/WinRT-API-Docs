---
-api-id: M:Windows.ApplicationModel.Appointments.AppointmentManagerForUser.ShowAppointmentDetailsAsync(System.String,Windows.Foundation.DateTime)
-api-type: winrt method
---

<!-- Method syntax
public Windows.Foundation.IAsyncAction ShowAppointmentDetailsAsync(System.String appointmentId, Windows.Foundation.DateTime instanceStartDate)
-->

# Windows.ApplicationModel.Appointments.AppointmentManagerForUser.ShowAppointmentDetailsAsync

## -description
Shows the Appointments provider Appointment Details UI, to enable the user to view the specified appointment.

## -parameters
### -param appointmentId
The [LocalId](appointment_localid.md) of the appointment to be displayed.

### -param instanceStartDate
A [DateTime](../windows.foundation/datetime.md) object with the start time of the appointment instance to be displayed.

## -returns
When this method returns, it does not return a result. On completion, the [AsyncActionCompletedHandler ](../windows.foundation/asyncactioncompletedhandler.md) specified by [get_Completed](http://msdn.microsoft.com/library/5050bf84-f9e0-4b3e-9252-6c5c1060826e) / [Completed](http://msdn.microsoft.com/library/eda29981-0c24-409a-8fb9-2dc2eb96d108) is invoked.

## -remarks

## -examples

## -see-also
[ShowAppointmentDetailsAsync(String)](appointmentmanagerforuser_showappointmentdetailsasync_1792084630.md)
## -capabilities
appointmentsSystem
