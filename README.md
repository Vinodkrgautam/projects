# projects
public void submit (View button) { 
final EditText nameField = (EditText) findViewById(R.id.EditTextName); 
String name = nameField.getText().toString(); 
final EditText emailField = (EditText) findViewById(R.id.EditTextEmail); 
String email = emailField.getText().toString(); 
final EditText phoneField = (EditText) findViewById(R.id.EditTextPhone); 
String phone = phoneField.getText().toString(); 
final EditText addressField = (EditText) 
findViewById(R.id.EditTextAddress); 
String address = addressField.getText().toString(); 
final EditText employeeId = (EditText) findViewById(R.id.EditTextId); 
String employmentId = employeeId.getText().toString(); 
Employee employee = new Employee(); 
employee.setName(name); 
employee.setEmail(email); 
employee.setPhone(phone); 
employee.setAddress(address); 
employee.setEmployeeId(employmentId); 
employee.saveEventually();
} 
<activity>
android:name=".SearchActivity" 
android:label="SampleApp" >
<intent-filter>
<action android:name=”android.intent.action.MAIN”/>
<category android:name=”android.intent.action.LAUNCHER”/>
</intent-filter>
<activity>
android:name=".MainActivity" 
android:label="SampleApp" >
</activity>
