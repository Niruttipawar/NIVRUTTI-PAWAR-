#include <stdio.h>
#include <string.h>

struct Person {
    char name[50];
    int age;
    float height;
};

int main() {
    struct Person person1;  // Create a Person variable

    // Assign values to the members
    strcpy(person1.name, "John");
    person1.age = 30;
    person1.height = 5.8;

    // Print the values
    printf("Name: %s\n", person1.name);
    printf("Age: %d\n", person1.age);
    printf("Height: %.2f\n", person1.height);

    return 0;
}
