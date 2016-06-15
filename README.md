# YNWPickerView pickview简单的封装

调用方法
YNWCustomPickerView *picker = [[YNWCustomPickerView alloc] init];
    picker.array = @[@"1", @"2", @"3", @"4", @"5"];
    [picker showPickViewSuperView:self.view ComplecationBlock:^(NSArray *array) {
        NSLog(@"%@", array);
    }];
