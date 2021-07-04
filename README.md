# program-to-read-and-print-an-employee-details-using-structure-
#include <stdio.h>
struct employee{
    char    name[30];
    int     empId;
    float   salary;
};
 
int main()
{
    
    struct employee emp;
     
    
    printf("\nEnter details :\n");
    printf("Name ?:");          gets(emp.name);
    printf("ID ?:");            scanf("%d",&emp.empId);
    printf("Salary ?:");        scanf("%f",&emp.salary);
     
    /*print employee details*/
    printf("\nEntered detail is:");
    printf("Name: %s"   ,emp.name);
    printf("Id: %d"     ,emp.empId);
    printf("Salary: %f\n",emp.salary);
    return 0;
}


 
Output

Enter details :
Name ?:Mike
ID ?:1120
Salary ?:76543

Entered detail is:
Name: Mike
Id: 1120
Salary: 76543.000000
